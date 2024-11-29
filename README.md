# Campster

This is a full-stack web application that allows users to create, browse, review, and manage campgrounds. With advanced features like image uploads, map integration, user authentication, and robust server-side validation, Campster provides a secure and engaging platform for camping enthusiasts.

---

## Tech Stack

- **Frontend**: HTML, CSS, JavaScript, Bootstrap, Embedded JavaScript (EJS)
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (Atlas)
- **Authentication**: Passport.js
- **Image Hosting**: Cloudinary
- **Map Integration**: MapBox
- **Tools**: Mongoose, Joi, Multer, Helmet, Postman, Visual Studio Code

**Live Website**: [Campster](https://campster-x7bp.onrender.com)

---

## Key Features

1. **Schema Validation**:
   - Used **Joi Schema** for robust server-side validation to prevent unauthorized operations via tools like Postman.
   - Ensures secure creation, deletion, and modification of campgrounds and reviews.

2. **Authentication**:
   - Implemented using **Passport.js**, leveraging the `pbkdf2` algorithm for secure encryption.
   - Supports login, registration, and session-based user authentication.

3. **Authorization**:
   - Each campground or review is linked to its creator using `_id` stored as an `author`.
   - Ensures users can only manage resources they own.

4. **Review System**:
   - Integrated **Starability.css** for visually appealing star-based reviews.

5. **Image Uploads**:
   - Used **Multer** for handling multiple image uploads.
   - Images are securely stored using **Cloudinary**.

6. **Maps Integration**:
   - Added dynamic maps to campgrounds using **MapBox** for an enhanced user experience.

7. **Content Security**:
   - Implemented **Helmet** to set secure HTTP response headers and enforce content security policies.

8. **Session Management**:
   - Sessions are stored using **mongo-connect**.
   - Used for flash messages and authentication.

9. **Database**:
   - All campground, user, and review data is stored in **MongoDB Atlas** for scalability and reliability.

10. **Responsive Design**:
    - Styled the website using **Bootstrap** for a modern and mobile-friendly interface.
