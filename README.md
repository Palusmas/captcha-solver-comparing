# captcha-solver-comparing
Comparing the solutions given by CAPTCHA with the answers it provides.



## Supported (That actually works) CAPTCHAs / Services

| Captcha Service    | Image Captcha | reCaptcha v2 | reCaptcha v2 Invisible | reCaptcha v2 Enterprise | reCaptcha v3 | reCaptcha v3 Enterprise | FunCaptcha | hCaptcha | hCaptcha Enterprise | Geetest V3 | Geetest V4 | DataDome Captcha | CyberSiara Captcha | AWS Captcha |
|--------------------|---------------|--------------|------------------------|-------------------------|--------------|-------------------------|------------|----------|---------------------|------------|------------|------------------|--------------------|-------------|
| capsolver.com      | ✅             | ✅            | ✅                      | ✅                       | ✅            | ✅                       | ✅          | ✅        | ✅                   | ✅          | ✅          | ✅                | ✅                  | ✅           |
| 2captcha.com       | ✅             | ✅            | ❌                      | ❌                       | ❌            | ❌                       | ❌          | ✅        | ❌                   | ✅          | ✅          | ❌                | ✅                  | ✅           |
| anti-captcha.com   | ✅             | ✅            | ❌                      | ❌                       | ❌            | ❌                       | ❌          | ✅        | ❌                   | ✅          | ✅          | ❌                | ❌                  | ❌           |
| azcaptcha.com      | ✅             | ✅            | ❌                      | ❌                       | ❌            | ❌                       | ❌          | ✅        | ❌                   | ✅          | ✅          | ❌                | ❌                  | ❌           |
| captcha.guru       | ✅             | ✅            | ❌                      | ❌                       | ❌            | ❌                       | ❌          | ✅        | ❌                   | ✅          | ✅          | ❌                | ❌                  | ❌           |
| cptch.net          | ✅             | ✅            | ❌                      | ❌                       | ❌            | ❌                       | ❌          | ✅        | ❌                   | ✅          | ✅          | ❌                | ❌                  | ❌           |
| deathbycaptcha.com | ✅             | ✅            | ❌                      | ❌                       | ❌            | ❌                       | ❌          | ✅        | ❌                   | ✅          | ✅          | ❌                | ❌                  | ❌           |
| rucaptcha.com      | ✅             | ✅            | ❌                      | ❌                       | ❌            | ❌                       | ❌          | ✅        | ❌                   | ✅          | ✅          | ❌                | ❌                  | ❌           |
| capmonster.com     | ✅             | ✅            | ❌                      | ❌                       | ❌            | ❌                       | ❌          | ✅        | ❌                   | ✅          | ✅          | ❌                | ❌                  | ❌           |


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
