# React-Form
The signupForm.js file consists of the code written for displaying the form asking the user for mail id,name,age,country,password.
/*import React, { useState } from 'react';

const SignupForm = () => {
  const [formData, setFormData] = useState({
    email: '',
    name: '',
    country: '',
    age: '',
    password: '',
  });

  const [errors, setErrors] = useState({
    email: '',
    name: '',
    country: '',
    age: '',
    password: '',
  });

  const [successMessage, setSuccessMessage] = useState('');
  const handleChange = (e) => {
    const { name, value } = e.target;
    setFormData({
      ...formData,
      [name]: value,
    });

    setErrors({
      ...errors,
      [name]: '',
    });
  };

  const handleSubmit = (e) => {
    e.preventDefault();
    let valid = true;

   
    const emailRegex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
    if (!emailRegex.test(formData.email)) {
      setErrors((prevErrors) => ({
        ...prevErrors,
        email: 'Invalid email format',
      }));
      valid = false;
    }

  
    if (formData.name.trim() === '') {
      setErrors((prevErrors) => ({
        ...prevErrors,
        name: 'Name is required',
      }));
      valid = false;
    }

   
    if (formData.country.trim() === '') {
      setErrors((prevErrors) => ({
        ...prevErrors,
        country: 'Country is required',
      }));
      valid = false;
    }

    
    if (formData.age === '' || isNaN(formData.age) || formData.age < 18) {
      setErrors((prevErrors) => ({
        ...prevErrors,
        age: 'Age must be at least 18',
      }));
      valid = false;
    }

   
    if (formData.password.length < 8) {
      setErrors((prevErrors) => ({
        ...prevErrors,
        password: 'Password must be at least 8 characters long',
      }));
      valid = false;
    }

    // Submit the form if valid
    if (valid) {
      
      console.log('Form submitted successfully');
      
      setSuccessMessage('Successfully Registered!');
    }
  };*/

  /*const { email, name, country, age, password } = formData;

  return (
    <div>
      <form onSubmit={handleSubmit}>
        <div>
          <label>Email:</label>
          <input type="email" name="email" value={email} onChange={handleChange} />
          {errors.email && <span className="error">{errors.email}</span>}
        </div>
        <div>
          <label>Name:</label>
          <input type="text" name="name" value={name} onChange={handleChange} />
          {errors.name && <span className="error">{errors.name}</span>}
        </div>
        <div>
          <label>Country:</label>
          <input type="text" name="country" value={country} onChange={handleChange} />
          {errors.country && <span className="error">{errors.country}</span>}
        </div>
        <div>
          <label>Age:</label>
          <input type="number" name="age" value={age} onChange={handleChange} />
          {errors.age && <span className="error">{errors.age}</span>}
        </div>
        <div>
          <label>Password:</label>
          <input type="password" name="password" value={password} onChange={handleChange} />
          {errors.password && <span className="error">{errors.password}</span>}
        </div>
        <button type="submit" disabled={!email || !name || !country || !age || !password}>
          Sign Up
        </button>
      </form>
      {successMessage && <div className="success-message">{successMessage}</div>}
    </div>
  );
};

export default SignupForm;*/
