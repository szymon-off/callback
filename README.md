
# Callback Code Auth Helper

Your best friend when it comes to simple OAuth2 authorization.




## How to use

Use https://szymon-off.github.io/callback as your callback URL for any OAuth2 application. 

OAuth2 applications will automatically add a code parameter which will be extracted and elegantly showcased to the user on the website.

You have to ask the user for the code.


## Demo

Click [here](https://szymon-off.github.io/callback?code=ABC-123-XYZ&label=Custom+OAuth+Token&bgColor=%23f5f7fa&boxColor=%23ffffff&inputColor=%23eef1f5&copyColor=%23007bff&borderRadius=16px&errorColor=%23ff4d4f) to view the demo. Take a look at the URL!
## Supported URL parameters

Additional URL parameters to customize the callback page. All of these are **optional**.

| Parameter      | Type     | Description                                                | Example Value             |
| -------------- | -------- | ---------------------------------------------------------- | ------------------------- |
| `callback`     | `string` | The code/token to display. Alias for `code`, `token`, etc. | `ABC123XYZ`               |
| `code`         | `string` | Alias for `callback`. Takes priority if present.           | `XYZ789`                  |
| `token`        | `string` | Alias for `callback`.                                      | `a1b2c3`                  |
| `access_token` | `string` | Alias for `callback`.                                      | `ya29.a0Af...`            |
| `auth_code`    | `string` | Alias for `callback`.                                      | `4/0AX4...`               |
| `error`        | `string` | Optional error message to display instead of a token.      | `Invalid+redirect_uri`    |
| `label`        | `string` | Label shown above the code field.                          | `OAuth Authorization`     |
| `bgColor`      | `color`  | Background color of the entire page.                       | `%23f0f0f0` (→ `#f0f0f0`) |
| `boxColor`     | `color`  | Background color of the main box.                          | `%23ffffff` (→ `#ffffff`) |
| `inputColor`   | `color`  | Background color of the input/textarea.                    | `%23eeeeee`               |
| `copyColor`    | `color`  | Color of the copy icon (SVG).                              | `%23007bff`               |
| `errorColor`   | `color`  | Text color used for the error message (in textarea).       | `%23ff4d4f`               |
| `borderRadius` | `string` | Border-radius CSS value for rounding the box.              | `12px`, `1rem`            |

