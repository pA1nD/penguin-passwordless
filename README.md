# penguin-passwordless

> Passwordless is a modern node.js module for [Express](http://expressjs.com/) that allows *authentication* and *authorization* without passwords by simply sending one-time password (OTPW) tokens via email or other means. It utilizes a very similar mechanism as the reset password feature of classic websites. The module was inspired by Justin Balthrop's article "[Passwords are Obsolete](https://medium.com/@ninjudd/passwords-are-obsolete-9ed56d483eb)"

Since penguin is unopinionated about authentication, this middleware provides authentication via passwordless.

Just plug it into your penguin.js based website using the middleware mechanism.

	$ npm i penguin-passwordless
	$ penguin run --middleware [ penguin-passwordless ]