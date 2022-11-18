## my solution about the follow test

* Write js code to display HTML5 validation errors below fields after submit.
* Example: https://nimb.ws/y4aqrw
* You can use default HTML5 methods: *checkValidity* and *validationMessage*.

```html
<form>
  <div>
    <label for="email">Email</label>
    <input id="email" type="email"  placeholder="example@example.com" required />
  </div>

  <div>
    <label for="alpha">Alphanumeric Only</label>
    <input id="alpha" type="text" pattern="[a-zA-Z0-9]+" required />
  </div>

  <div>
    <label for="age">Age (min: 21)</label>
    <input id="age" type="number" min="21" required />
  </div>

  <input type="submit" value="Log In" />
</form>
```

In the solution that I made each field is validate in real time. Don't need click in the submit button to know if some field is not valid! I used a javascript method *checkValidity* and an HTML5 method *validationMessage* for the validation

NOTE: with the new release of **BOOTSTRAP 5** a new one great feature is the **validation form** [check it out](https://getbootstrap.com/docs/5.0/forms/validation/) maybe this simple test

18th November 2022
[@astr0surf3r](https://github.com/Astr0surf3r)