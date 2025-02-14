# **Contact Form Task**  

## **Aim**  
To create a **Contact Form** using **HTML** that allows users to enter their name, email, and message, along with social media links.  

---

## **Procedure**  
1. **Create an HTML file (`contact.html`)** to design the form layout.  
2. Use the `<table>` element for structured form alignment.  
3. Include the following fields:  
   - **Text input (`<input type="text">`)** for Name.  
   - **Email input (`<input type="email">`)** for Email.  
   - **Textarea (`<textarea>`)** for Message input.  
   - **Submit button (`<input type="submit">`)** to send the form data.  
4. Add **social media links** (Facebook, Twitter, Instagram, LinkedIn).  
5. Include a **footer section** with copyright information.  
6. Save and test the form in a browser.  

---

## **Program (`contact.html`)**  
```html
<!DOCTYPE html>
<html>

<head>
    <title>Contact Form</title>
</head>

<body>
    <center>
        <h2>Vidya Neela M</h2>
        <p>Web Developer</p>
        <table>
            <tr>
                <td>Name: </td>
                <td><input type="text" placeholder="Enter Your Name"></td>
            </tr>
            <tr>
                <td>Email: </td>
                <td><input type="email" placeholder="Enter Your Email"></td>
            </tr>
            <tr>
                <td>Message: </td>
                <td><textarea placeholder="Your Message" name="Message" rows="4" cols="25"></textarea></td>
            </tr>
            <tr>
                <td colspan="2" align="center"><input type="submit"></td>
            </tr>
            <tr>
                <td colspan="2" align="center">
                    <p>Social Media:
                        <a href="https://www.facebook.com">Facebook</a> |
                        <a href="https://www.twitter.com">Twitter</a> |
                        <a href="https://www.instagram.com">Instagram</a> |
                        <a href="https://www.linkedin.com">LinkedIn</a>
                    </p>
                </td>
            </tr>
            <tr>
                <td colspan="2" align="center">
                    <p>&copy; Vidya Neela</p>
                </td>
            </tr>
        </table>
    </center>
</body>

</html>
```

---

## **Output Screenshot**  
![image](https://github.com/user-attachments/assets/c560cc20-57da-4617-a5ad-371f1bd1088f)
  

---

## **Expected Output**  
- A **contact form** with fields for **Name, Email, and Message**.  
- A **Submit button** to send data.  
- Social media links for easy access.  
- A footer displaying the **copyright notice**.  

---

## **Observations**  
✔ The form collects **user details** efficiently.  
✔ Social media links are integrated for **better connectivity**.  
✔ The form structure is **clear and simple**.  

---

## **Conclusion**  
The **Contact Form** was successfully implemented using **HTML**, improving my understanding of **form handling and structured layout design**.  

---
