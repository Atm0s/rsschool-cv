# Vadim Nikitchuk

## Contacts


- Email: atm0s84@gmail.com
- GitHub: [Atm0s](https://github.com/Atm0s)
- Telegram: [@Atm0zz](https://t.me/Atm0zz)
- [LinkedIn](https://www.linkedin.com/in/vadim-nikitchuk-17256173/)<br>

## About me
Hello! Most of my life I worked as a system administrator. But two years ago I decided to change my life and I started to learn FrontEnd Development. 
I enjoy learning and developing new things and skills that can improve quality of my life and other people ones. I think I have good interpersonal skills. I am reliable and dependable and often seek new responsibilities within a wide range of employment areas.

## Skills
- HTML
- CSS
- Git
- JavaScript ([codewars.com profile](https://www.codewars.com/users/Atm0s/stats))

## Code Example
**Codewars KATA:**
*Complete rgb function so that passing in RGB decimal values will result in a hexadecimal representation being returned. Valid decimal values for RGB are 0 - 255. Any values that fall out of that range must be rounded to the closest valid value.*

```javascript
function rgb(r, g, b) {
  let result = [];
  let a = 0
  for (val in arguments) {
    if (arguments[val] > 255) (a = 255);
    else if (arguments[val] < 0) (a = 0);
    else (a = arguments[val])
    if (a.toString(16).length === 1) (a = '0' + a.toString(16))
    result.push(a.toString(16)) 
  }
  return result.join('').toUpperCase()
}
```

## Education
- University: Russian State University of Tourism and Service (RSUTS)

## Courses:
- Rolling Scopes School
- CS50 lectures
- HTML Academy

## Languages
- Russian - native speaker
- English - B2-A1