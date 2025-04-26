# web422-assignment-6-solved
**TO GET THIS SOLUTION VISIT:** [WEB422 Assignment 6 Solved](https://www.ankitcodinghub.com/product/web422-assignment-6-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;100786&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;WEB422 Assignment 6 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
For this assignment, we will continue our development effort from Assignment 5.

<strong>Note</strong>: If you require a working version of assignment 5 to continue with this assignment, please email your professor.

For this assignment, we will restrict access to our app to only users who have registered.&nbsp; Registered users will also have the benefit of having their favourites and history lists saved, so that they can return to them later and on a different device.&nbsp; To achieve this, we will primarily be working with concepts from Weeks 8 and 9, such as <a href="https://webprogrammingforappsandservices.sdds.ca/Introduction-JWT/json-web-tokens-jwt">incorporating JWT in a Web API</a><a href="https://webprogrammingforappsandservices.sdds.ca/Introduction-JWT/json-web-tokens-jwt">,</a> as well as UI considerations for <a href="https://webprogrammingforappsandservices.sdds.ca/Authentication-In-Next/authentication-logging-in">working with a secured web API in</a> <a href="https://webprogrammingforappsandservices.sdds.ca/Authentication-In-Next/authentication-logging-in">Next.js</a>

Sample Solution:

<a href="https://web422-a6-fall-2022.vercel.app/">https://web422</a><a href="https://web422-a6-fall-2022.vercel.app/">–</a><a href="https://web422-a6-fall-2022.vercel.app/">a6</a><a href="https://web422-a6-fall-2022.vercel.app/">–</a><a href="https://web422-a6-fall-2022.vercel.app/">fall</a><a href="https://web422-a6-fall-2022.vercel.app/">–</a><a href="https://web422-a6-fall-2022.vercel.app/">2022.vercel.app</a>

<h1>Step 1: Creating a “User” API</h1>
To enable our “Met Artwork” App to register / authenticate users and persist their “favourites” / “history” lists, we will need to create our own “User” API and publish it online (Cyclic).&nbsp; However, before we begin writing code we must first create a “users” Database on MongoDB Atlas to persist the data.&nbsp; This can be accomplished by:

&nbsp;

<ul>
<li>Logging into your account on MongoDB Atlas: <a href="https://account.mongodb.com/account/login">https://account.mongodb.com/account/login</a></li>
<li>Click on the “Browse Collections” button in the “Database Deployments” screen (next to the “…” button)</li>
<li>Once MongoDB Atlas is finished “Retrieving list of databases and collections…”, you should see a list of your databases with a “+ Create Database” button.</li>
<li>Choose whatever “DATABASE NAME” you like, and add “users” as your “COLLECTION NAME”</li>
<li>Once this is complete, go back to the previous view (“Database Deployments”) and click the “Connect” button, followed by “Connect your application”</li>
<li>Copy the “connection string” – it should look something like:</li>
</ul>
&nbsp;

mongodb+srv://YourMongoDBUser<strong>:&lt;password&gt;</strong>@clusterInfo.abc123.mongodb.net/?retryWrites=true&amp;w=majo rity

<ul>
<li>Add your Database User password in place of <strong>&lt;password&gt;</strong> and your “DATABASE NAME” (from above) after the text <strong>net/</strong> in the above connection string</li>
<li>Save your updated “connection string” value (we’ll need it when we create our User API)</li>
</ul>
&nbsp;

Now that we have a database created on MongoDB Atlas, we can proceed to create our User API using Node / Express.&nbsp; To begin, you can use the following code as a starting point:

&nbsp;

<a href="https://pat-crawford-sdds.netlify.app/shared/fall-2022/web422/A6/user-api.zip">https://pat</a><a href="https://pat-crawford-sdds.netlify.app/shared/fall-2022/web422/A6/user-api.zip">–</a><a href="https://pat-crawford-sdds.netlify.app/shared/fall-2022/web422/A6/user-api.zip">crawford</a><a href="https://pat-crawford-sdds.netlify.app/shared/fall-2022/web422/A6/user-api.zip">–</a><a href="https://pat-crawford-sdds.netlify.app/shared/fall-2022/web422/A6/user-api.zip">sdds.netlify.app/shared/fall</a><a href="https://pat-crawford-sdds.netlify.app/shared/fall-2022/web422/A6/user-api.zip">–</a><a href="https://pat-crawford-sdds.netlify.app/shared/fall-2022/web422/A6/user-api.zip">2022/web422/A6/user</a><a href="https://pat-crawford-sdds.netlify.app/shared/fall-2022/web422/A6/user-api.zip">–</a><a href="https://pat-crawford-sdds.netlify.app/shared/fall-2022/web422/A6/user-api.zip">api.zip</a>

&nbsp;

You will notice that the starter code contains everything that we will need to start building our API.&nbsp; The only task left is for us to secure the routes and publish the server online (Cyclic).&nbsp; You will notice however that (like assignment 1) this solution also makes use of “.env”.&nbsp; Once the code is online, you will once again need to ensure that Cyclic is aware of the values for the variables.

&nbsp;

At the moment, .env contains two values: <strong>MONGO_URL</strong> and <strong>JWT_SECRET</strong>.&nbsp; <strong>MONGO_URL</strong> is used by the “userservice” module and <strong>JWT_SECRET</strong> will be used by your code to sign a JWT payload as well as to validate an incoming JWT.

&nbsp;

Begin by updating this file, such that the <strong>MONGO_URL</strong> is your updated “connection string” (from above, without quotes) and your <strong>JWT_SECRET</strong> is a “long, unguessable string” (also without quotes).&nbsp; You may wish to use a Password Generator, ie: <a href="https://www.lastpass.com/password-generator">https://www.lastpass.com/password</a><a href="https://www.lastpass.com/password-generator">–</a><a href="https://www.lastpass.com/password-generator">generator</a> to help generate a secret.

&nbsp;

With our environment variables in place, we can now concentrate on securing our routes.&nbsp; This will involve correctly setting up “<a href="https://www.npmjs.com/package/passport">passport</a><a href="https://www.npmjs.com/package/passport">“</a> to use a “<a href="https://www.npmjs.com/package/passport-jwt">JwtStrategy</a><a href="https://www.npmjs.com/package/passport-jwt">“</a> (passportJWT.Strategy) and initializing the passport middleware for use in our server.&nbsp; Everything required to accomplish this task is outlined in the <a href="https://webprogrammingforappsandservices.sdds.ca/Introduction-JWT/json-web-tokens-jwt">JSON Web</a> <a href="https://webprogrammingforappsandservices.sdds.ca/Introduction-JWT/json-web-tokens-jwt">Tokens (JWT)</a> section of the course notes.&nbsp; The primary differences are:

&nbsp;

<ul>
<li>We will be using the value of “secretOrKey” from <strong>env.JWT_SECRET</strong> (from our .env file) instead of hardcoding it in our server.js</li>
<li>The Strategy will <strong>not</strong> be making use of “fullName” (jwt_payload.fullName) or “role” (jwt_payload.role), since our User data does not contain these properties</li>
</ul>
&nbsp;

The following is a list of specifications required for our User API once “passport” has been set up (<strong>HINT</strong> most of the code described below is very similar to the code outlined in <a href="https://webprogrammingforappsandservices.sdds.ca/Introduction-JWT/json-web-tokens-jwt">JSON Web Tokens (JWT)</a><a href="https://webprogrammingforappsandservices.sdds.ca/Introduction-JWT/json-web-tokens-jwt">,</a> so make sure you have them close by for reference):

&nbsp;

&nbsp;

<h2>POST /api/user/login</h2>
<strong>&nbsp;</strong>

This is the only route that contains logic that needs to be updated, specifically:

&nbsp;

<ul>
<li>If the user is valid (ie, the “checkUser()” promise resolves successfully) use the returned “user” object to generate a “payload” object consisting of two properties: <strong>_id</strong> and <strong>userName</strong> that match the value returned in the “user” object. This will be the content of the JWT sent back to the client.</li>
</ul>
&nbsp;

Sign the payload using “jwt” (Hint: Using the “<a href="https://www.npmjs.com/package/jsonwebtoken">jsonwebtoken</a><a href="https://www.npmjs.com/package/jsonwebtoken">“</a> module) with the secret from <strong>process.env.JWT_SECRET</strong> (from our .env file).

&nbsp;

Once you have your signed token, include it a “token” property within the JSON “message” returned to the client.

&nbsp;

<h2>Routes Protected Using the passport.authenticate() Middleware</h2>
<strong>&nbsp;</strong>

The final step in securing the API is to make sure that the majority of our routes are protected from unauthorized access.&nbsp; This involves correctly adding the “passport.authenticate()” middleware to the following routes:

&nbsp;

<ul>
<li>GET “/api/user/favourites”</li>
<li>PUT “/api/user/favourites/:id”</li>
<li>DELETE “/api/user/favourites/:id”</li>
<li>GET “/api/user/history”</li>
<li>PUT “/api/user/history/:id”</li>
<li>DELETE “/api/user/history/:id”</li>
</ul>
&nbsp;

With these changes in place, your User API should now be complete.&nbsp; The final step is to push it to Cyclic (recall: <a href="https://web322.ca/getting-started-with-cyclic">Getting Started With Cyclic</a> from WEB322 and our Assignment 1 in this course).

&nbsp;

However, there is one small addition that we need to ensure is in place for our User API to work once it’s on Cyclic – Setting up the <strong>MONGO_URL </strong>and<strong> JWT_SECRET </strong>Config Variables:

&nbsp;

<ul>
<li>Login to Cyclic to see your dashboard</li>
<li>Click on the “wrench” (Options and Configs) icon for your newly created application</li>
<li>Click on the “Variables” tab at the top (next to “Environments”)</li>
<li>Enter your JWT_SECRET (from .env) in the corresponding textbox (without quotes)</li>
<li>Similarly, enter MONGO_URL in the corresponding textbox (without quotes) and hit the “Save” button</li>
</ul>
&nbsp;

NOTE: If Cyclic did not automatically detect the “JWT_SECRET” and “MONGO_URL” environment variables, you will have to add them using “Create New”

This will ensure that when we refer to either MONGO_URL or JWT_SECRET in our code using <strong>process.env</strong>, we will end up with the correct value.

&nbsp;

This completes the first part of the assignment (setting up your User API).&nbsp; Please record the URI, ie: “https://some-randomName.cyclic.app/api/user” somewhere handy, as this will be the “NEXT_PUBLIC_API_URL” used in our Next.js application.

&nbsp;

&nbsp;

<h1>Step 2: Updating our Next.js App (utility / “lib” functions)</h1>
&nbsp;

Now that we have our User API in place, we can make some key changes in our Next.js App to ensure that only registered / logged in users can view the data, as well as to finally persist their favourites / history lists in our mongoDB “users” collection.

&nbsp;

<strong>HINT: </strong>Once again, most of the code described below is very similar to the code outlined in the <a href="https://webprogrammingforappsandservices.sdds.ca/Authentication-In-Next/authentication-logging-in">Authentication</a> <a href="https://webprogrammingforappsandservices.sdds.ca/Authentication-In-Next/authentication-logging-in">(Logging In)</a> section of the notes, so make sure you have them close by for reference.

&nbsp;

&nbsp;

<h2>Adding .env</h2>
<strong>&nbsp;</strong>

Since we just completed setting up our User API on Cyclic, why don’t we start by adding it to a new <strong>.env</strong> file as: NEXT_PUBLIC_API_URL, ie:

&nbsp;

NEXT_PUBLIC_API_URL=”<strong>https://some-randomName.cyclic.app/api/user</strong>”

&nbsp;

&nbsp;

<h2>Creating an “Authenticate” library</h2>
<strong>&nbsp;</strong>

We will be requiring users to be authenticated to view / interact with our data, so our next step should be to write the logic to enable this feature in a separate library, ie:&nbsp; “my-app<strong>/lib/authenticate.js</strong>“:

&nbsp;

Once you have created the “authenticate.js” file, you can use <a href="https://webprogrammingforappsandservices.sdds.ca/Authentication-In-Next/authentication-logging-in#building-an-authentication-library">Building an “Authentication” Library</a> from the course notes as a starting point:

&nbsp;

<ul>
<li>Include the following functions from the notes (these can remain the same)</li>
</ul>
&nbsp;

<ul>
<li><a href="https://webprogrammingforappsandservices.sdds.ca/Authentication-In-Next/authentication-logging-in#function-settoken">setToken(token)</a> o <a href="https://webprogrammingforappsandservices.sdds.ca/Authentication-In-Next/authentication-logging-in#function-gettoken">getToken()</a> o <a href="https://webprogrammingforappsandservices.sdds.ca/Authentication-In-Next/authentication-logging-in#function-removetoken">removeToken</a><a href="https://webprogrammingforappsandservices.sdds.ca/Authentication-In-Next/authentication-logging-in#function-removetoken">(</a><u>)</u> o <a href="https://webprogrammingforappsandservices.sdds.ca/Authentication-In-Next/authentication-logging-in#function-readtoken">readToken()</a> o <a href="https://webprogrammingforappsandservices.sdds.ca/Authentication-In-Next/authentication-logging-in#function-isauthenticated">isAuthenticated()</a></li>
<li><a href="https://webprogrammingforappsandservices.sdds.ca/Authentication-In-Next/authentication-logging-in#function-authenticateuser">authenticateUser(user, password)</a></li>
</ul>
&nbsp;

<ul>
<li>We must also create another function: <strong>registerUser(user, password, password2)</strong>. This function is almost identical to “authenticateUser(user, password), however it has the following key differences:</li>
</ul>
&nbsp;

<ul>
<li>Makes a “post” request to “/register” instead of “/login”</li>
</ul>
&nbsp;

<ul>
<li>In addition to providing “userName” and “password” in the <strong>body</strong> of the request, it also passes “password2”</li>
</ul>
&nbsp;

<ul>
<li>If it was successful (ie: status is 200), we <strong>do not</strong> invoke the “setToken()” function – we simply return <strong>true</strong></li>
</ul>
<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<h2>Creating a “UserData” library</h2>
<strong>&nbsp;</strong>

For this application, we will require a second library to work with the new functionality available from our User API, specifically: adding, modifying and deleting favourites and history items.&nbsp; To begin, create the file “userData.js” within the newly create “lib” folder, ie: “my-app<strong>/lib/userData.js</strong>“: Once you have created the “userData.js” file, add the following functions:

&nbsp;

<strong>NOTE: </strong>Each of the following functions <strong>must</strong> be defined as “asynchronous” (ie: “async”) and follows the same logic, ie (pseudocode):

&nbsp;

&nbsp;

Make a GET, PUT or DELETE request using fetch to the appropriate route starting with process.env.NEXT_PUBLIC_API_URL, ie: process.env.NEXT_PUBLIC_API_URL/<strong>favourites</strong>/someID, etc.

&nbsp;

(For every request, make <strong>sure</strong> to include an “Authorization” header with a value in the format “JWT<strong> <em>TOKEN</em></strong>“, where <strong><em>TOKEN</em></strong> is the value obtained from executing the “getToken()” function (defined above) from your “Authenticate” library

&nbsp;

If the operation was successful (ie: status is 200), return the data (ie: the result from calling res.json())

&nbsp;

If the operation was <strong>not</strong> successful (ie: status was not 200), return an empty array, ie: []

&nbsp;

&nbsp;

Apply the above logic to each of the below functions:

&nbsp;

<ul>
<li>addToFavourites(id) – PUT request to /favourites/<strong>id</strong></li>
</ul>
&nbsp;

<ul>
<li>removeFromFavourites(id) – DELETE request to /favourites/<strong>id</strong></li>
</ul>
&nbsp;

<ul>
<li>getFavourites() – GET request to /favourites</li>
</ul>
&nbsp;

<ul>
<li>addToHistory(id) – PUT request to /history/<strong>id</strong></li>
</ul>
&nbsp;

<ul>
<li>removeFromHistory(id) – DELETE request to /history/<strong>id </strong></li>
</ul>
&nbsp;

<ul>
<li>getHistory() – GET request to /history</li>
</ul>
&nbsp;

<h1>Step 3: Updating our Next.js App (Login and Register components)</h1>
&nbsp;

Before we start working with the history / favourites directly in the database using our new “lib” functions, we should add the components / pages to enable the user to register and log into the system.

&nbsp;

&nbsp;

<h2>Creating a “login” Page</h2>
&nbsp;

To begin, start by creating a new file: <strong>login.js</strong> within the <strong>pages</strong> directory of your app.

&nbsp;

Once this is created, proceed to follow the course notes on: “<a href="https://webprogrammingforappsandservices.sdds.ca/Authentication-In-Next/authentication-logging-in#creating-a-login-page">Creating A ‘Login’ Page</a><a href="https://webprogrammingforappsandservices.sdds.ca/Authentication-In-Next/authentication-logging-in#creating-a-login-page">“</a> (making sure to redirect to “/favourites” instead of “/vehicles” after a successful login).

&nbsp;

After implementing the “Alert” to show errors, test the app by running “npm run dev” and navigating manually to the <strong>/login</strong> route.

&nbsp;

You should see that you are unable to login, as no users are currently in the system.&nbsp; However, you should be able to confirm that the request is being made and that the errors are showing correctly within the “Alert” component.

&nbsp;

Before moving on to the “Register” component and re-testing the login functionality, we must write some additional code to ensure that the atoms defined in store.js are correctly updated with the values from the back end once the user logs in.&nbsp; To achieve this, we must:

&nbsp;

<ul>
<li>Reference both the “favouritesAtom” and the “searchHistoryAtom” using the “useAtom” hook (HINT: Be sure to include the corresponding import statements).</li>
</ul>
&nbsp;

<ul>
<li>Import both the “getFavourites” and “getHistory” functions from our newly created “userData.js” file</li>
</ul>
&nbsp;

<ul>
<li>Create an “asynchronous” (async) function called “updateAtoms” within the “Login” component that updates both the favourites and history with the return values from the “getFavourites” and “getHistory” functions, ie:</li>
</ul>
&nbsp;

async function updateAtoms(){

setFavouritesList(await getFavourites());&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; setSearchHistory(await getHistory());

}

&nbsp;

<ul>
<li>Invoke the “updateAtoms” function once the user has been authenticated, before redirecting to the “/favourites” route, ie:</li>
</ul>
&nbsp;

await updateAtoms();

&nbsp;

Here, we can pull the correct favourites and history lists from the API for the logged in user, before they begin to navigate the site.

&nbsp;

&nbsp;

<h2>Creating a “register” Page</h2>
<strong>&nbsp;</strong>

Next, we will focus on creating the “register” page, so that we may create users in the system and correctly test the new functionality.&nbsp; Begin by creating a new file: <strong>register.js</strong> within the <strong>pages</strong> directory of your app.

&nbsp;

Once this is created, you can use the now completed <strong>login.js</strong> file as a starting point.&nbsp; Proceed to copy the whole file into “register.js” and rename the component from “Login” to “Register”.&nbsp; Next, make the following modifications to the code:

&nbsp;

<ul>
<li>Replace the import for “authenticateUser” with “<strong>registerUser</strong>“, ie:</li>
</ul>
<strong>&nbsp;</strong>

import { <strong>registerUser</strong> } from “../lib/authenticate”;

&nbsp;

<ul>
<li>Remove the imports for “getFavourites”, “getHistory”, “useAtom”, “favouritesAtom” and “searchHistoryAtom”</li>
</ul>
&nbsp;

<ul>
<li>Remove the “useAtom()” function calls from within the “Register” component function</li>
</ul>
&nbsp;

<ul>
<li>Remove the “updateAtoms()” function <strong><em>and</em></strong> the code that invokes it (ie: await updateAtoms())</li>
</ul>
&nbsp;

<ul>
<li>Add a “password2” value to the state (using useState) with a default value of “”</li>
</ul>
&nbsp;

<ul>
<li>When the form is submitted, instead of invoking “authenticateUser”, invoke “registerUser” with the “password2” value from the state, ie:</li>
</ul>
&nbsp;

await registerUser(user, password, password2);

&nbsp;

<ul>
<li>Instead of redirecting to “/favourites” when the user has logged in, redirect to “/login” once the user has registered</li>
</ul>
&nbsp;

<ul>
<li>Change the card content to read something related to registering (instead of logging in), ie:</li>
</ul>
&nbsp;

<strong>Register </strong>

Register for an account:

&nbsp;

<ul>
<li>Add another &lt;Form.Group&gt; to capture the “password2” value. Be sure to include an appropriate label, ie: “Confirm Password”</li>
</ul>
&nbsp;

<ul>
<li>Finally, change the button text from “Login” to “Register”</li>
</ul>
&nbsp;

With all of these changes in place, we should have a functioning “Register” component / page.&nbsp; To test this, ensure that your app is running (npm run dev) and manually navigate to the “/register” route and attempt to register for an account on the system.

&nbsp;

<strong>NOTE: </strong>Be sure to test all aspects of the functionality, ie: registering for a duplicate user, mismatched passwords, etc.

&nbsp;

Once you have successfully registered for an account, you should be redirected to “/login”.&nbsp; Proceed to log in with your newly created account.&nbsp; You should be redirected to “/favourites” (although there will be no favourites shown) and the JWT should be added to local storage.

&nbsp;

&nbsp;

<h1>Step 4: Updating our Next.js App (New “Favourites” functionality)</h1>
&nbsp;

With our system now able to allow users to log in and store the resulting JWT in local storage, let’s update the favourites functionality to use the new API / functionality:

&nbsp;

<h2>Updating “ArtworkCardDetail”</h2>
<strong>&nbsp;</strong>

The main UI for adding / removing favourites exists primarily within the “ArtworkCardDetail” component (specifically, the “+ favourite” button).&nbsp; To add the new functionality here, we must make the following changes to the “<strong>ArtworkCardDetail.js</strong>” file, containing the “ArtworkCardDetail” component:

&nbsp;

<ul>
<li>Import both the “addtoFavourites” and “removeFromFavourites” functions from our “userData.js” file</li>
</ul>
&nbsp;

<ul>
<li>Change the default value for the “showAdded” state value to <strong>false</strong></li>
</ul>
&nbsp;

<ul>
<li>Use the React “useEffect” hook to update showAdded instead, ie:</li>
</ul>
&nbsp;

useEffect(()=&gt;{

setShowAdded(favouritesList?.includes(objectID)) }, [favouritesList])

&nbsp;

<ul>
<li>Modify the “favouritesClicked” function so that its “asynchronous” (async)</li>
</ul>
&nbsp;

<ul>
<li>Change the code to “setFavouritesList” (ie: updating the atom value) according to the following:</li>
</ul>
&nbsp;

<ul>
<li>If showAdded is <strong>true </strong>(ie: it <em>is </em>in the favourites list), set the favourites list by invoking:</li>
</ul>
setFavouritesList(await removeFromFavourites(<strong>objectID value</strong>)) (where <strong>objectID value</strong>, is the value passed by “props” to the component)

&nbsp;

<ul>
<li>If showAdded is <strong>false </strong>(ie: it <em>is not </em>in the favourites list), set the favourites list by invoking:</li>
</ul>
setFavouritesList(await addToFavourites(<strong>objectID value</strong>))

&nbsp;

<h2>Updating “Favourites”</h2>
<strong>&nbsp;</strong>

Finally, we must make one small update to the “Favourites” component (“pages/favourites.js”).&nbsp; Since the process of populating the favourites list is not instantaneous (ie: pulling it from the API), we want to make sure that our favourites list doesn’t temporarily show the “Nothing Here” message.&nbsp; To resolve this, simply add the following line of code <em>below</em> the line to “<strong>useAtom()</strong>” within the component function (ie: after our hooks):

&nbsp;

if(!favouritesList) return null;

&nbsp;

Additionally, we must ensure that we remove the <em>default</em> value (empty array) for the <strong>favouritesAtom</strong> within the “store.js” file, ie:

&nbsp;

export const favouritesAtom = atom();

&nbsp;

If you test the functionality now, you should see that you’re able to add favourites as before, after first logging in with your test user (created when testing the register functionality).&nbsp; However, if you inspect the user in the database, you should also see that the item.

&nbsp;

Unfortunately, if you refresh the “favourites” page, you will see that once again your favourites list is empty.&nbsp; We will fix this issue later on in the assignment.

&nbsp;

&nbsp;

<h1>Step 5: Updating our Next.js App (New “History” functionality)</h1>
&nbsp;

The next step is to use a similar strategy to update our “history” list, such that the values are added / removed from the database.

&nbsp;

<h2>Updating “MainNav”</h2>
&nbsp;

Begin by opening the “MainNav” Component (components/MainNav.js) and making the following changes:

&nbsp;

<ul>
<li>Import the “addtoHistory” function from our “userData.js” file</li>
</ul>
&nbsp;

<ul>
<li>Modify the “submitForm” function so that its “asynchronous” (async)</li>
</ul>
&nbsp;

<ul>
<li>Change the code to “setSearchHistory” (ie: updating the atom value) to the following</li>
</ul>
&nbsp;

o setSearchHistory(await addToHistory(`title=true&amp;q=${<strong>searchField</strong>}`))

&nbsp;

(where <strong>searchField</strong> is the value of the “search” form field in the navigation bar)

&nbsp;

<h2>Updating “AdvancedSearch” (search.js)</h2>
&nbsp;

Next, we must update the logic in our “AdvancedSearch” component (pages/search.js) so that it <em>also</em> makes use of our new logic for persisting the data:

&nbsp;

<ul>
<li>Import the “addtoHistory” function from our “userData.js” file</li>
</ul>
&nbsp;

<ul>
<li>Modify the “submitForm” function so that its “asynchronous” (async)</li>
</ul>
&nbsp;

<ul>
<li>Change the code to “setSearchHistory” (ie: updating the atom value) to the following</li>
</ul>
&nbsp;

o setSearchHistory(await addToHistory(<strong>queryString</strong>))

&nbsp;

(where <strong>queryString</strong> is the calculated value generated within the “submitForm” function)

&nbsp;

<h2>Updating “History”</h2>
<strong>&nbsp;</strong>

Finally, we must make a few small changes to the “History” component (“pages/history.js”). As with our favourites component, the process of populating the history list is not instantaneous (ie: pulling it from the API).&nbsp; Therefore, we want to make sure that our history list doesn’t temporarily show the “Nothing Here” message.&nbsp; To resolve this, simply add the following line of code <em>below</em> the line to “<strong>useRouter()</strong>” within the component function (ie: after our hooks):

&nbsp;

if(!favouritesList) return null;

&nbsp;

Also as before, we must ensure that we remove the <em>default</em> value (empty array) for the <strong>searchHistoryAtom</strong> within the “store.js” file, ie:

&nbsp;

export const searchHistoryAtom = atom();

&nbsp;

However, since it’s also possible to manipulate the history list on this page (ie: removing history items), we must also make the following additional changes to the “History” component (“pages/history”):

&nbsp;

<ul>
<li>Import the “removeHistory” function from our “userData.js” file</li>
</ul>
&nbsp;

<ul>
<li>Modify the “removeHistoryClicked” function so that its “asynchronous” (async)</li>
</ul>
&nbsp;

<ul>
<li>Change the code to “setSearchHistory” (ie: updating the atom value) to the following</li>
</ul>
&nbsp;

o setSearchHistory(await removeFromHistory(<strong>searchHistory</strong>[index]))

&nbsp;

(where <strong>searchHistory</strong> is the value from your “searchHistoryAtom”)

&nbsp;

If you test the functionality now, you should see that you’re able to add history as before, after first logging in with your test user (created when testing the register functionality).&nbsp; However, if you inspect the user in the database, you should also see that the item.

&nbsp;

Unfortunately, (as with the favourites page) if you refresh the “history” page, you will see that your history list is empty.&nbsp; Once again, we will fix this issue later on in the assignment.

&nbsp;

&nbsp;

<h1>Step 6: Updating our Next.js App (“Route Guard” functionality)</h1>
&nbsp;

To ensure that users can only access the search / favourites functionality after they have successfully logged into the system, we must implement a “Route Guard” as discussed in the course notes.&nbsp; Additionally, we will add some logic to populate our “atoms” when the route guard is first mounted – this will help us resolve the issue of our “favourites” and “history” lists disappearing when we refresh the pages.

&nbsp;

Begin by recreating the <a href="https://webprogrammingforappsandservices.sdds.ca/Authentication-In-Next/UI-considerations#creating-a-route-guard-component">“Route Guard” example from the notes</a><a href="https://webprogrammingforappsandservices.sdds.ca/Authentication-In-Next/UI-considerations#creating-a-route-guard-component">,</a> including:

&nbsp;

<ul>
<li>Adding the complete “RouteGuard.js” file within the “components” directory.</li>
<li>Updating _app.js to use the new &lt;RouteGuard&gt;…&lt;/RouteGuard&gt; Component</li>
</ul>
&nbsp;

Once this is complete, we must make the following changes to the “RouteGuard” component:

&nbsp;

<ul>
<li>Add “/register” to the PUBLIC_PATHS array</li>
<li>Reference both the “favouritesAtom” and the “searchHistoryAtom” using the “useAtom” hook (HINT: Be sure to include the corresponding import statements).</li>
</ul>
&nbsp;

<ul>
<li>Import both the “getFavourites” and “getHistory” functions from our newly created “userData.js” file</li>
</ul>
&nbsp;

<ul>
<li>Copy the “asynchronous” (async) function “updateAtoms()” defined in the “Login” component (above) and paste it within the “RouteGuard” component function</li>
</ul>
&nbsp;

<ul>
<li>Invoke the “updateAtoms()” at the beginning of the “useEffect()” hook function (this will ensure that our atoms are up to date when the user refreshes the page)</li>
</ul>
&nbsp;

With this step completed, try testing your app again.&nbsp; You should see that the favourites and history lists are saved for the logged in user and they also remain in the UI even after a page is refreshed.&nbsp; Additionally, if you manually remove the token from LocalStorage (“Application Tab” in the Chrome Dev Tools) and try refreshing or accessing a secure page, you should be redirected back to the “login” page.

&nbsp;

&nbsp;

<h1>Step 7: Updating our Next.js App (“Navbar” UI)</h1>
&nbsp;

As with the <a href="https://webprogrammingforappsandservices.sdds.ca/Authentication-In-Next/UI-considerations#updating-the-navigation-component">example from the notes</a><a href="https://webprogrammingforappsandservices.sdds.ca/Authentication-In-Next/UI-considerations#updating-the-navigation-component">,</a> we must also update our “Navbar” (ie: “MainNav” component) to reflect whether or not the current user is logged in and give them the ability to “log out”:

&nbsp;

First, to create the “Log out” functionality, define a function (ie: “logout()” within the “MainNav” (components/MainNav.js) component function), according the following guidelines:

&nbsp;

<ul>
<li>It must set the “expanded” state value to false (in order to collapse the menu)</li>
<li>Invoke the “removeToken()” function from the “authenticate” lib</li>
<li>Use the “useRouter()” hook (router.push()) to redirect the user to the “/login” page</li>
</ul>
&nbsp;

With our “logout()” function in place, we can finally concentrate on updating the Navbar content as well as showing / hiding specific elements within &lt;Navbar.Collapse&gt;…&lt;/Navbar.Collapse&gt;.

&nbsp;

Before we begin however, we must ensure that we have access to current value of the token by invoking the “readToken()” function from the “authenticate” lib (see: “<a href="https://webprogrammingforappsandservices.sdds.ca/Authentication-In-Next/UI-considerations#updating-the-navigation-component">Updating the Navigation Component</a><a href="https://webprogrammingforappsandservices.sdds.ca/Authentication-In-Next/UI-considerations#updating-the-navigation-component">“</a>).

&nbsp;

Now that we potentially have the token (stored in a <strong>token</strong> variable), we can use the value to update the Navbar to show user content / add new items:

&nbsp;

<ul>
<li>If the user is logged in (ie: value of <strong>token</strong> is <em>truthy</em>)</li>
</ul>
&nbsp;

<ul>
<li>Show the “Advanced Search” navigation item o Show the “Search” form o Show the “User Name” dropdown
<ul>
<li>Update the text “User Name” to show the <strong>userName</strong> value from the <strong>token</strong></li>
<li>Add a new &lt;NavDropdown.Item&gt;…&lt;/NavDropdown.Item&gt; item with the text <strong>Logout</strong> that, when clicked, will invoke the newly created “logout()” function (above)</li>
<li>(Optionally) remove the “active” property from the “Favourites” and “Search History” items</li>
</ul>
</li>
</ul>
&nbsp;

<ul>
<li>If the user is not logged in (ie: the value of <strong>token</strong> is <em>falsy</em>)</li>
</ul>
&nbsp;

<ul>
<li>Show a new &lt;Nav&gt;…&lt;/Nav&gt; element (beneath the &lt;Nav className=”me-auto”&gt;…&lt;/Nav&gt; element that contains two links for <strong>Register</strong> (“/register”) and <strong>Login</strong> (“/login”)</li>
</ul>
&nbsp;

<strong>NOTE: </strong>For each of the links, be sure to include the <strong>active</strong> property and to set the “expanded” state value to <strong>false</strong> when clicked (use the “/” and “/search” links as examples)

&nbsp;

<h1>Step 8: Publishing our App on Vercel</h1>
&nbsp;

If you test the app locally now, you should see that it functions the same as the example code, ie: you can create multiple accounts and for each account, store different favourites / search histories.

&nbsp;

As a final step, we must place this code online.&nbsp; For this purpose, we will use “Vercel”, as in the course notes.&nbsp; For this final part of the assignment, follow the “<a href="https://webprogrammingforappsandservices.sdds.ca/Deployment-Automated-Testing/continuous-deployment#introduction-to-vercel">Introduction to Vercel</a><a href="https://webprogrammingforappsandservices.sdds.ca/Deployment-Automated-Testing/continuous-deployment#introduction-to-vercel">“</a> and record the production URL for your assignment submission.

&nbsp;

<strong>NOTE: </strong>The instructions assume that you have already pushed your Next.js code to a private GitHub repository.

&nbsp;

&nbsp;

Assignment Submission:

<ul>
<li>Add the following declaration at the top of your index file:</li>
</ul>
/********************************************************************************* *&nbsp; WEB422 – Assignment 06

<ul>
<li>I declare that this assignment is my own work in accordance with Seneca Academic Policy.&nbsp; No part of this *&nbsp; assignment has been copied manually or electronically from any other source (including web sites) or&nbsp; *&nbsp; distributed to other students.</li>
</ul>
*

<ul>
<li>Name: ______________________ Student ID: ______________ Date: ________________</li>
</ul>
*

<ul>
<li>Vercel App (Deployed) Link: _____________________________________________________</li>
</ul>
*

********************************************************************************/

&nbsp;

<ul>
<li>Next, Compress (.zip) <strong><u>both</u></strong> your <strong><u>User API</u> </strong>and your <strong><u>js App</u> </strong>source code folders together (omitting the node_modules folder, as usual) in order to produce a single .zip file for your submission.</li>
<li>Submit your compressed file (containing both your User API and the Node.js App) to My.Seneca under <strong>Assignments</strong> -&gt; <strong>Assignment 6</strong></li>
</ul>
Important Note:

<ul>
<li><strong>NO LATE SUBMISSIONS</strong> for assignments. Late assignment submissions will not be accepted and will receive a <strong>grade of zero (0)</strong>.</li>
<li>After the end (11:59PM) of the due date, the assignment submission link on My.Seneca will no longer be available.</li>
<li>Submitted assignments must run locally, ie: start up errors causing the assignment/app to fail on startup will result in a <strong>grade of zero (0)</strong> for the assignment.</li>
</ul>
