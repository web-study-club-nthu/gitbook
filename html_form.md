#Form
* A form: `<form>`
    * Action attribute: `action`
    * Method attribute: `method`
        * `get`
        * `post`

### Input elements
* A basic input element: `<input>`
    * Type attribute: `type`, means the input type of the input.
    * Name attribute: `name`, means the group of the options.
    * Value attribute: `value`, means the data to send.
* Single line text: `<input type="text"/>` / `<input type="email"/>` / `<input type="url"/>`
* Single line private text: `<input type="password"/>`
    * Size attribute: `size`
    * Max Length attribute: `maxlength`
* Text Area: `<textarea>`
* Single option choose: `<input type="radio"/>`
    * Radio with the same `name` attribute can choose one of them only.
* Multi option choose: `<input type="checkbox"/>`
    * Pre checked attribute: `checked`, means to check the option when the form creates.
* Dropdown menu: `<select>`
    * Item of the dropdown menu: `option`
* File upload: `<input type="file"/>`
    * Form method must use `post`.
* Submit button: `<input type="submit"/>`
    * Value attribute: `value`, means the words displaying on the button.
* Button: `<button>`

### Validation and Styling
* Only in HTML5
* Required attribute: `required`, value can only be `required`
* Lable for input elements: `lable`. If the lable dosen't contains the input element, must have a `for` attribute which value is the `id` of the input.
```
<form>
    <h1>Not Actually Working - Member Sign Up Page</h1>
    <p><lable>
        Member ID:
        <input type="text" name="id"/>
    </lable></p>

    <p><lable>
        Email:
        <input type="email" name="email" required="required"/>
    </lable></p>

    <p><lable>
        Password:
        <input type="password" name="pswd"/>
    </lable></p>

    <p><lable>
        Gender:
        <input type="radio" name="gender" value="boy"/> Male
        <input type="radio" name="gender" value="girl"/> Female
        <input type="radio" name="gender" value="other"/> Others
    </lable></p>

    <p><lable>
        Photo upload:
        <input type="file" name="photo"/>
    </lable></p>
    <p>
        Self introduction<br>
        <textarea name="intro"></textarea>
    </p>
    <input type="submit" value="Send!">
</form>
```