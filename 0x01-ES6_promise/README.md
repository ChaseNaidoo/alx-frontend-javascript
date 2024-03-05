# 0-promise.js
Return a Promise using this prototype function getResponseFromAPI()

# 1-promise.js
Using the prototype below, return a promise. The parameter is a boolean.

# 2-then.js
Append three handlers to the function:
- When the Promise resolves, return an object with the following attributes
  - status: 200
  - body: success
- When the Promise rejects, return an empty Error object
- For every resolution, log Got a response from the API to the console

# 3-all.js
In this file, import uploadPhoto and createUser from utils.js

# 4-user-promise.js
Using the following prototype, return a resolved promise with this object

# 5-photo-reject.js
Write and export a function named uploadPhoto. It should accept one argument fileName (string).
The function should return a Promise rejecting with an Error and the string $fileName cannot be processed

# 6-final-user.js
Import signUpUser from 4-user-promise.js and uploadPhoto from 5-photo-reject.js.
Write and export a function named handleProfileSignup. It should accept three arguments firstName (string), lastName (string), and fileName (string). The function should call the two other functions.

# 7-load_balancer.js
Write and export a function named loadBalancer. It should accept two arguments chinaDownload (Promise) and USDownload (Promise).
The function should return the value returned by the promise that resolved the first.

# 8-try.js
Write a function named divideFunction that will accept two arguments: numerator (Number) and denominator (Number).
When the denominator argument is equal to 0, the function should throw a new error with the message cannot divide by 0. Otherwise it should return the numerator divided by the denominator.

# 9-try.js
Write a function named guardrail that will accept one argument mathFunction (Function).
This function should create and return an array named queue.
When the mathFunction function is executed, the value returned by the function should be appended to the queue. If this function throws an error, the error message should be appended to the queue. In every case, the message Guardrail was processed should be added to the queue.

# 100-await.js
Import uploadPhoto and createUser from utils.js
Write an async function named asyncUploadUser that will call these two functions and return an object with the following format
If one of the async function fails, return an empty object.
