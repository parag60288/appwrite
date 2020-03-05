let sdk = new Appwrite();

sdk
    .setProject('5df5acd0d48c2') // Your project ID
;

let promise = sdk.avatars.getImage('https://example.com');

promise.then(function (response) {
    console.log(response); // Success
}, function (error) {
    console.log(error); // Failure
});