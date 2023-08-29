# assignment - "User should be able to sign up, verify their email, register a TOTP and login"
- Need one form with name, email and mobile field.
- Use Formik for validation and other form APIs.
- validation using Yup for email and mobile and all are reuired field.
- Email verification will be send once sign up completed.
- On email, will share form to set a password. Once email verify user will be added in the system.
- While login, user wil verify username ans password.
- To validate 2-factor authentcation, we can use other application to share OTP (like google authenticator).
- Once it validate, will redirect to our dashboard/home page
- To test scinarios with component level, feature level we can use RTL or Enzyme test libabries with Jest test framework
- We will prefer React Testing Library (RTL) with Jest to test all our test cases, because enzyme require more coding and unnecessary accessiblity to DOM.

