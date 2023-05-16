# **Task description**

## **Theme: Toy Management System**

A company is seeking a web developer who can create a full-stack website to build a website for their Toy Management system. You are required to focus on a specific toy category, such as Toy Cars(sports, racing, regular, etc. toy car), Action figure toys(marvel, avengers, star wars, transformers, etc.), animal toys(teddy bear, horse, dinosaur, dogs, cat, unicorn, cows, etc.), sports toys(miniature or plastic version of sports accessories), toy robots, dolls(baby dolls, barbie, american girl, etc), disney dolls (disney princes, frozen dolls, animation characters, etc.), toy makeup, video game toys, Building and Construction Toys, Educational and Learning Toys(science kits, math learning toys, engineering kits, engineering tools), cooking Toys, Arts and Crafts Toys, Musical Toys(miniature musical instruments), Board Games and Puzzles, Electronic Toys, lego sets(lego city, lego star wars, lego architecture, lego disney), sand castle building toys, etc. Thus, if you select disney dolls toys, your website will only showcase toys related to that particular category.

Make sure your website design is unique. Visit ThemeForest, Dribble, google, etc., to get some ideas.

If possible, you can explore component libraries other than DaisyUI. Remember, a unique project will add more value to your portfolio.
<hr/>
<br/>

## **Main Requirements**
1. Focus on making the website visually appealing. Ensure that
    - color contrast is pleasing to the eye
    - the website does not have a `gobindo design`
    - the website has proper alignment and space
    - If needed, customize the design of any component you are taking from any component library. (For example, you are using daisy ui & has taken card component from daisy, if needed customize the styling the card to make it reasonable, rather just copy & paste it.)
    <br/>
    <br/>
    
    > **Note:** Your website can not be related to your previous assignments layout/ design or any practice project shown in the course modules or our conceptual sessions. Ex: You can't copy any design or similar functionality/ layout of
    - Dragon news
    - Espresso Emporium
    - Car Doctor
    - Travel guru 
    - Volunteer network
    - Job Portal Website or Any conceptual session projects, or any project showed in our course.
   
    <br/>

    **If any similarities are found, you will get zero(0) as a penalty.**

<br/>

2. Make sure to keep the navbar and footer on all the pages **except on the 404 page**. Create a reasonable and meaningful footer. <b>(including website logo, name, copyright, some contact information, social media links, address, etc.)</b>

<br/>

3. Your website should have a navbar with the **Website logo, Website name, Home, Blog, My Toys, All Toys, Add A Toy** and **User profile picture**. 
    > **Note:** The **User profile picture, Add A Toy** and **My Toys** on the navbar are conditional based on login. If the user is logged in, the navbar will show the profile picture; otherwise, it will show the **Login button**. If the username is available, the user's name will be visible when the mouse hovers over the profile picture.

<br/>

4. **`Login & Registration systems:`** On the Registration page and Login page, display relevant error messages when necessary.

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

5. **`Home page:`**
    - **Banner section** -A slider/banner/ a meaningful section. 

    - **Gallery Section** - Show relevant pictures. Try to make it attractive.
    - **Shop by category**- Implement a tab system for **Shop by category** section. Explore [React-tabs](https://www.npmjs.com/package/react-tabs) or you can implement this using custom css. There will be 3 tabs each containing sub-categories of the category you have chosen. 
    <br/>

    > For example, if the website is based on **Educational and learning toys**, the sub-categories for the **3** tabs can be **Math Toys, Language Toys, engineering toys, and Science Toys, etc.**. you need at least 3 categories.
    <br/>

    > Each tab will have minimum 2 data and each data will have the following information:
    - Picture, 
    - Name,
    - Price, 
    - Rating and 
    - View Details button. 
    
    <br/>
            
    > **Note:** When a user is not logged in and if he/ she clicks on the View Details button, notify the user with a message **“You have to log in first to add this item to your list”** by using a toast/ notification/ anything. Also, redirect him/ her to the login page. Without login, you can not visit the single toy details page.

    - **Extra Section:** Add two relevant sections. Try to make them attractive.


<br/>

6. **`Blog page:`** Create a Blog where you will have to answer the following questions:
    
    - What is access token and refresh token works and where should we store them in the client side?
    - Compare between SQL and NoSQL databases?
    - what is express js? What are the alternative to expressJS? 
    - what is react `Suspense`? when will you use it?
    
    <br/>

<br/>

7. **`All Toys`** page: Create an All Toys page where you will see the toys all the users have added in the tabular form. Each row of the All Toys table/list will have the following information:

    -   Name of the person who posted the toy
    -   Email of the person who posted the toy
    -   Toy name
    -   Sub-category
    -   View Details button
    <br/>

    > Above the table, implement a search system based on the **Toy name.**
    <br/>

    Without logging in, if a user clicks on the **View Details** button, he/she will be redirected to the Login Page. Make sure to take the user to the Details Page, after the user successfully logs in.

<br/>

8. **`Single toy details route will be a private route:`**
    
    > After clicking on the **View Details** button, he/ she will be redirected to the **Toys Details** route **( /toy/:id )** containing the information **( picture, name, price, rating and detail description)**

<br/>

9. **`Add A Toy page will be a private route:`** 
    <br/>

    > Create an **Add A Toy** page where there will be a form having the following fields:
    - Picture url of the toy,
    - Name,
    - Sub-category, ( For example: if the website is based on Educational and learning toys, the sub-categories can be Math Toys, Language Toys and Science Toys.)
    - Price, 
    - Rating, 
    - Detail description

<br/>

10. **`My Toys page will be private routes:`** If a user logs in, he/she will see the My Toys page where it will show all the toys information he/she has added from the Add A Toy page in a tabular form. Each row will have update and delete buttons. 
    <br/>

    - **Update Action** - If he/she clicks the `update` button, he/ she can update the Toy information (Picture, Name, Sub-category, Price, Rating, Detail description) <br/><br/>
        > **Note:** Here, you can show the update form in a modal or in another route.
    
    <br/>

    - **Delete Action** - If she/he clicks on the delete button, the Toy will be removed from the list. Before the delete ask for a delete confirmation.
    <br/>
    <br/>
        > **Note:** If a user logs in he/she will only see the toys he/she has added. The user cannot see the toys other users added.
    <br/>

    **Bonus task: See the bonus point 4**

<br/>

11. For all the CRUD operations, show relevant toast/ notification/ anything with a meaningful message 

<br/>

12. **`404 page:`** 

    > Create a 404 page. Add any interesting jpg/ gif on the 404 page. **Do not add header & footer in this page.** Just add a jpg/ gif & a **Back to home** button. **Back to home** button will redirect the user to the home page.

<br/>

13. Use the Environment variable to hide the Firebase config keys and mongodb credentials. 

<hr/>
<br/>

## **Bonus Requirements**

1. **Commits & readme:**

    - Minimum 18 meaningful git commits on the client-side repository.
    - Minimum 8 meaningful commits on the server-side repository.
    - Create a readme for client-side and write about your project (at least 5 bullet points). **Do not forget to add your client side live link of your website here.**

<br/>

2. **Reload :** If you reload the protected/private routes (after login), this page will not redirect the user to the login page. Instead, it will keep the logged-in user on the protected route. 

2. Make your website mobile & desktop responsive (tablet responsive is optional)

<br/>

4. Use the [AOS Package](https://www.npmjs.com/package/aos) in the home page. At least in one place in the home page. Using AOS in other pages is optional

<br/>

5. On **My Toys** page, you have to implement a sorting system where you will sort the toys in **descending** and **ascending** orders based on the **price**. (Explore mongodb sorting operation & implement it on backend). The design of the sorting system depends on you.

<br/>

6. Give your website name. The website title will be changed according to the route you are clicking. Suppose, your website name is PHero. Then, on the **‘about’** route, your website title will be **‘PHero | About us’**.

7. add a spinner to the my toys page. 

8. Make the component name, folder structure, route name meaningful. If needed add comments. 

<br/>

---
<br/>

## **Optional (But Highly Recommended):**

1. Implement JWT token in your routes.

<br/>

2. Add a spinner when the data is in loading state. You can add a gif/jpg, use any packages or customize it using css.

<br/>

3. **Interesting part:** 

    > Each blog will contain a question, an answer and a pin icon. You can display them however you want. When a user clicks on a pin icon, the pin icon will become blue (or any dark color) and the pinned blog will be shown on the homepage. However, if a user clicks on the blog that is already pinned, the blog will be unpinned and that blog will not appear on the homepage. Make sure to make the pin icon white when the blog unpins.
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

1. You can use a local image or host image anywhere or use pictures from the internet. And it's ok if you have the image url, but the image link doesn't work. 
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
`The best things of life are on the other side of the pain.` 
