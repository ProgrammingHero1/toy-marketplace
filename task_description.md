# **Toy Marketplace**

A company is seeking a web developer who can create a simple full-stack Toy Marketplace website. You are required to focus on a specific toy category, such as-

    - Toy Cars(sports car, truck, regular car, mini fire truck, mini police car, etc.)
    - Action figure toys(marvel, avengers, star wars, transformers, etc.)
    - Animal toys(teddy bear, horse, dinosaur, dogs, cat, unicorn, cows, etc.)
    - Sports toys(miniature or plastic version of sports accessories) 
    - Toy robots
    - Dolls(baby dolls, barbie, American girl, etc)
    - Disney dolls (Disney princes, frozen dolls, animation characters, donald duck, etc.), 
    - Girls' makeup toy, 
    - Video game toys, 
    - Building and Construction Toys, 
    - Educational and Learning Toys(science kits, math learning toys, engineering kits, engineering tools), 
    - Cooking Toys, 
    - Arts and Crafts Toys, 
    - Musical Toys(miniature musical instruments), 
    - Board Games and Puzzles, 
    - Electronic Toys, 
    - Lego sets(lego city, lego star wars, lego architecture, lego cars), 
    - Sand castle building toys, etc. 
    - Any other types of toys
    
 If you select Disney dolls toys, your website will only showcase toys related to that particular types. Do not mix different types of toys in your website.

Make sure your website design is unique. Visit ThemeForest, Dribble, google, etc., to get some ideas.

You can explore component libraries other than DaisyUI. Remember, a unique project will add more value to your portfolio.
<hr/>
<br/>
🚩: 0 [ If we have any update we will mention it here ] 
<br/>

## **Main Requirements**
1. Focus on making the website visually appealing. Ensure that
    - Color contrast is pleasing to the eye
    - The website does not have a `gobindo design`
    - The website has proper alignment and space
    - If needed, customize the design of any component you are taking from any component library. (For example, you are using daisy ui & have taken a card component from Daisy, if needed, customize the styling of the card to make it reasonable rather than just copy & paste it.)
    <br/>
    <br/>
    
    > **Note:** Your website can not be related to your previous assignments' layout/ design or any practice project shown in the course modules or our conceptual sessions. Ex: You can't copy any design or similar functionality/ layout of
    - Dragon news
    - Espresso Emporium
    - Car Doctor
    - Travel guru 
    - Volunteer network
    - Job Portal Website, Any conceptual session projects, or projects showed in our course.
    - Any of your previous assignments
   
    <br/>

    **If any similarities are found, you will get zero(0) as a penalty.**

<br/>

2. Make sure to keep the navbar and footer on all the pages **except on the 404-page**. Create a reasonable and meaningful footer. <b>(including website logo, name, copyright, some contact information, social media links, address, etc.)</b>

<br/>

3. Your website should have a navbar with the **Website logo, Website name, Home, All Toys, My Toys, Add A Toy, Blogs,** and **User profile picture**. 
    > **Note:** The **User profile picture, Add A Toy** and **My Toys** on the navbar are conditional based on login. If the user is logged in, the navbar will show the profile picture; otherwise, it will show the **Login button**. If the username is available, the user's name will be visible when the mouse hovers over the profile picture.

<br/>

4. **`Login & Registration systems:`** On the Registration and Login pages, display relevant error messages when necessary.

    > **Login Page:** When a user clicks on the login button, they will be redirected to the login page having the following:

    - Email/Password
    - Google Sign-in
    - A link that will redirect to the registration page

    <br/>

    > **Registration Page:**  The Registration page will have the Email/Password form having the following fields:

    - Name
    - Email
    - Password
    - Photo URL

    <br/>

    > **Note:** Do not enforce the email verification method, as it will inconvenience the examiner. If you want, you can add email verification after receiving the assignment result.

<br/>

5. **` Home page:`**
    - **Banner section** -A slider/banner/ a meaningful section. 

    - **Gallery Section** - Show relevant pictures. Try to make it attractive.
    - **Shop by category**- Implement a tab system for **Shop by category** section. Explore [React-tabs](https://www.npmjs.com/package/react-tabs), or you can implement this using custom CSS. There will be 3 tabs, each containing sub-categories of the category you have chosen. 
    <br/>

    > For example, if the website is based on **Educational and learning toys**, the sub-categories for the **3** tabs can be **Math Toys, Language Toys, engineering toys, and Science Toys, etc.**. You need at least 3 sub-categories.
    <br/>

    > Each tab will have minimum 2 toys, and each toy will have the following information:
    - Picture, 
    - Name,
    - Price, 
    - Rating and 
    - View Details button. 
    
    <br/>
            
    > **Note:** When a user is not logged in and if he/ she clicks on the View Details button, notify the user with a message **“You have to log in first to view details”** by using a toast/ notification/ anything. Also, redirect him/ her to the login page. Without a login, you can not visit the single toy details page.

    - **Extra Section:** Add two relevant sections. Try to make them attractive.


<br/>

6. **` Blogs`** page: Create a Blog where you will have to answer the following questions:
    
    - What is an access token and refresh token? How do they work and where should we store them on the client-side?
    - Compare SQL and NoSQL databases?
    - What is express js? What is Nest JS (google it)? 
    - What is MongoDB aggregate and how does it work (google it)?
    
    <br/>

<br/>

7. **` All Toys`** page: Create an All Toys page where you will see the toys all the users have added in the tabular form. Each row of the All Toys table/list will have the following information:

    -   Seller: (if available) show the name of the person who posted the toy
    -   Toy Name
    -   Sub-category
    -   Price
    -   Available Quantity
    -   View Details button
    <br/>

    > Show 20 results by default by using `limit`
    > 
    > Implement a search system on this page, based on the **Toy name.**
    <br/>

    Without logging in, if a user clicks on the **View Details** button, they will be redirected to the Login Page. Make sure to take the user to the Details Page after the user successfully logs in.

<br/>

8. **`Single toy details route will be a private route:`**
    
    > After clicking on the **View Details** button, he/ she will be redirected to the **Toys Details** route **( /toy/:id )** containing the information **( picture, toy name, seller name, seller email, price, rating, available quantity, and detail description)**
    > 
    > (optional) If possible, display the view details in a modal

<br/>

9. **` Add A Toy page will be a private route:`** 
    <br/>

    > Create an **Add A Toy** page where there will be a form having the following fields:
    - Picture URL of the toy,
    - Name,
    - seller name (if available from the logged in user)
    - seller email (info from the logged in user)
    - Sub-category ( For example: if the website is based on Educational and learning toys, the sub-categories can be Math Toys, Language Toys, and Science Toys.)
    - Price, 
    - Rating, 
    - Available quantity
    - Detail description

<br/>

10. **`My Toys page will be private routes:`** If a user logs in, they will see the My Toys page, which it will show all the toys information they have added from the Add A Toy page in a tabular form. Each row will have an update and delete button. 
    <br/>

    - **Update Action** - If they click the `update` button, they can update the Toy information (Price, available quantity, Detail description) <br/><br/>
        > **Note:** you can show the update form in a modal or another route.
    
    <br/>

    - **Delete Action** - If they click the delete button, the Toy will be removed from the list. Before the delete, ask for a delete confirmation.
    <br/>
    <br/>
        > **Note:** If a user logs in they will only see the toys they have added. The user cannot see the toys other users added.
    <br/>

 

<br/>

11. For all the CRUD operations, show relevant toast/ notification/ anything with a meaningful message 

<br/>

12. **`404 page:`** 

    > Create a 404 page. Add any interesting jpg/ gif on the 404 page. **Do not add header & footer on this page.** Just add a jpg/ gif & a **Back to home** button. The**Back to home** button will redirect the user to the home page.

<br/>

13. Use the Environment variable to hide the Firebase config keys and Mongodb credentials. 

<hr/>
<br/>

## **Bonus Requirements**

1. **Commits & readme:**

    - Minimum 18 meaningful git commits on the client-side repository.
    - Minimum 8 meaningful commits on the server-side repository.
    - Create a readme for client-side and write about your project (at least 5 bullet points). ** Remember to add your client-side live link to your website here.**

<br/>

2. **Reload:** If you reload the protected/private routes (after login), this page will not redirect the user to the login page. Instead, it will keep the logged-in user on the protected route. 

2. Make Home page of your website mobile & desktop responsive (tablet responsive is optional)

<br/>

4. Use the [AOS Package](https://www.npmjs.com/package/aos) in the home page. At least in one place on the home page. Using AOS on other pages is optional.

<br/>

5. On the **My Toys** page, you must implement a sorting system to sort the toys in **descending** and **ascending** orders based on the **price**. (Explore MongoDB sorting operation & implement it on the backend). The design of the sorting system depends on you.

<br/>

6. Give your website name. The website title will be changed according to the route you are clicking. Suppose your website name is PHero. Then, on the **‘about’** route, your website title will be **‘PHero | About us’**.

7.  Make the component name, folder structure, and route name meaningful. If needed, add comments. 

<br/>

---
<br/>

## **Optional (But Highly Recommended):**

1. Implement a JWT token in your routes.

<br/>

2. Add a spinner when the data is in a loading state. You can add a gif/jpg, use any package or customize it using CSS.

<br/>

3. **Interesting part:** 

    > Each blog will contain a question, an answer, and a pin icon. You can display them however you want. When a user clicks on a pin icon, the pin icon will become blue (or any dark color), and the pinned blog will be shown on the homepage. However, if a user clicks on the already pinned blog, the blog will be unpinned, and that blog will not appear on the homepage. Make sure to make the pin icon white when the blog unpins.
    <br/>
    When a user is not logged in, the pin button is disabled.

<br/>

4. **Little Bit Advanced:** Add more toys for each sub-category. You can add pagination in your tab system.

<br/>

5. Add extra features of your own. This will help you in the future to differentiate your project from others.

<br/>
<hr/>
<br/>

### **Additional information:**

1. You can use a local or host image anywhere or use pictures from the internet. And it's ok if you have the image url, but the image link doesn't work. 
2. You can use vanilla CSS or any CSS library (Bootstrap, tailwind) you want. If you wish, you can use both Bootstrap and react-bootstrap. Also, if you want, you can use any tailwind component library such as DaisyUI, etc.
3. Try to host your site on Firebase (Netlify hosting will need some extra configurations)
4. Host your server-side application on Vercel. If needed, you can host somewhere else as well.
4. Make Sure you deploy server-side and client-side on the first day. If you have any issues with hosting or GitHub push, please join the "Github and deploy" related support session.

<br/>
<hr/>
<br/>

### **What to submit:**

1. Your client-side code GitHub repository
2. Your server-side code GitHub repository
3. Your live website link

<br/>
<hr/>
<br/>

### **Some Guidelines:**

1. Do not waste much time on the website idea. Just spend 15-20 minutes deciding, find a sample website, and start working on it.
2. Do not waste much time finding the right image. You can always start with a simple idea. Make the website and then add different images.
3. Don't look at the overall task list. Just take one task at a time and do it. Once it's done, pick the next task. If you get stuck on a particular task, move on to the next task.
4. Stay calm, think before coding, and work sequentially. You will make it.
5. Be strategic about the electricity issue. 
6. use `chatgpt` to generate JSON data. You can use chatGPT for Yother purposes as well. 

<br/>
<hr/>
<br/>

### No Pain, No Gain:
`The most beautiful moments in life comes after going through hardships and challenges.` 
