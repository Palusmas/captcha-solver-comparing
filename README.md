# captcha-solver-comparing
Comparing the solutions given by CAPTCHA with the answers it provides.


## Supported CAPTCHAs / Services

| CAPTCHA\\Service | Image   | Text | reCAPTCHA v2 | reCAPTCHA v2 invisible | reCAPTCHA v2 enterprise | reCAPTCHA v3 | reCAPTCHA v3 enterprise | FunCaptcha | KeyCAPTCHA | Geetest | Geetest v4 | hCaptcha | Capy | DataDome Captcha | CyberSiara Captcha | AWS Captcha |
|------------------|---------|------|--------------|--------------|------------|------------|---------|------------|----------|------|
| capsolver.com    | ✅      | ✅    | ✅            | ✅            | ✅          | ✅          | ✅       | ✅          | ✅        | ✅    |
| 2captcha.com     | ✅      | ✅    | ✅            | ✅            | ✅          | ✅          | ✅       | ✅          | ✅        | ✅    |
| anti-captcha.com | ✅     | ❌    | ✅            | ✅            | ✅          | ✅          | ✅       | ✅          | ✅        | ❌    |
| azcaptcha.com    | ✅     | ❌    | ✅            | ✅            | ✅          | ❌          | ✅       | ❌          | ✅        | ❌    |
| captcha.guru     | ✅     | ❌    | ✅            | ✅            | ❌          | ❌          | ✅       | ❌          | ✅        | ❌    |
| cptch.net        | ✅     | ❌    | ✅            | ✅            | ❌          | ❌          | ❌       | ❌          | ❌        | ❌    |
| deathbycaptcha   | ✅     | ❌    | ✅            | ✅            | ❌          | ❌          | ✅       | ❌          | ✅        | ❌    |
| rucaptcha.com    | ✅     | ✅    | ✅            | ✅            | ✅          | ✅          | ✅       | ✅          | ✅        | ✅    |

### Image CAPTCHA

| Service          | Regular | Case Sensitive | Phrase | Numbers only | Letters only | Math | Length | Language      | Comment for worker |
|------------------|---------|----------------|--------|--------------|--------------|------|--------|---------------|--------------------|
| 2captcha.com     | ✅       | ✅              | ✅      | ✅            | ✅            | ✅    | ✅      | Cyrillic/Latin| ✅                  |
| anti-captcha.com | ✅       | ✅              | ✅      | ✅            | ✅            | ✅    | ✅      | Latin         | ✅                  |
| azcaptcha.com    | ✅       | ❌              | ❌      | ❌            | ❌            | ❌    | ❌      | Latin         | ✅                  |
| captcha.guru     | ✅       | ❌              | ❌      | ❌            | ❌            | ❌    | ❌      | Latin         | ✅                  |
| cptch.net        | ✅       | ❌              | ❌      | ❌            | ❌            | ❌    | ❌      | Cyrillic/Latin| ❌                  |
| deathbycaptcha.com | ✅     | ❌              | ❌      | ❌            | ❌            | ❌    | ❌      | Latin         | ❌                  |
| rucaptcha.com    | ✅       | ✅              | ✅      | ✅            | ✅            | ✅    | ✅      | Cyrillic/Latin| ✅                  |
