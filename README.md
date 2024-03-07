# Bradesco Automation Project with Selenium

## Description
This project uses Selenium to automate refinancing operations on Bradesco's website, including proxy manipulation, solving CAPTCHAs with 2Captcha, and advanced DOM interactions.

## Technologies Used
- Python
- Selenium WebDriver
- 2Captcha API
- Fake UserAgent

## Configuration
`config.py` defines credentials for proxy and user (`login_proxy`, `senha_proxy`, `login_usuario`, `senha_usuario`).

## Main Functions
- `login_bradesco(usuario, senha, cpf)`: Log in and prepare for refinancing operations.
- `consulta_bradesco(cpf, driver)`: Perform refinancing queries, solve CAPTCHAs, and extract detailed information.

## Usage
1. Configure `config.py`.
2. Run `bradesco_oficial.py`.

## Dependencies
- selenium
- webdriver-manager
- fake_useragent
- twocaptcha
- pandas
- pynput
