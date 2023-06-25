## CustomForm

📝 **Instructions**

1. Create a new React component named `CustomForm`.

2. Import the `useState` hook from the `react` library.

3. Inside the `CustomForm` component, define a state variable named `formData` using the `useState` hook. Initialize it with an object containing the following properties:

   - `firstName` (string)
   - `lastName` (string)
   - `email` (string)

4. Implement the `handleInputChange` function that updates the state `formData` when the input values change. This function should:

   - Take an `event` parameter representing the input change event.
   - Destructure the `name` and `value` properties from the `event.target`.
   - Update the state by calling `setFormData` and spreading the current `formData` object, while updating the property specified by `name` with the new `value`.

5. Render a `<div>` element with the class name "container".

6. Inside the `<div>` element, create a `<form>` element.

7. Inside the form, create the following input fields using the provided information:

   - First Name:

     - `<input>` element with the following attributes:
       - `type="text"`
       - `name="firstName"`
       - `value={formData.firstName}`
       - `onChange={handleInputChange}`
       - `className="form-control"`

   - Last Name:

     - `<input>` element with the following attributes:
       - `type="text"`
       - `name="lastName"`
       - `value={formData.lastName}`
       - `onChange={handleInputChange}`
       - `className="form-control"`

   - Email:
     - `<input>` element with the following attributes:
       - `type="email"`
       - `name="email"`
       - `value={formData.email}`
       - `onChange={handleInputChange}`
       - `className="form-control"`

8. Remember to close all elements properly.

9. Export the `CustomForm` component as the default export of the module.

```note
you can use bootstrap for styling
```

🚀 **Happy coding**
