# Importing a Postman C ollection

The collections in the repo are called `Vivantio*.postman_collection.json`. Note that the collections are set to use **Basic Auth** with the **Username** and **Password** being populated from variables set in the Vivantio environment. The collections are populated with three Postman tests:

```JavaScript

These tests should be passing green for a successful API call.


pm.test("Status code is 200", function () {
    pm.response.to.have.status(200);
});

pm.test("Successful status is true", function () {
    pm.expect(pm.response.json().Successful).to.equal(true);
});

pm.test("No error messages returned", function () {
    pm.expect(pm.response.json().ErrorMessages.length).to.equal(0);
});
