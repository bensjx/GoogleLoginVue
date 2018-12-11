Demo: https://bensjx.github.io/GoogleLoginVue

## How to use:

1. Go to firebase console, under develop -> authentication -> sign-in methods, enable google login.
2. Under the google login portion, go to Web Client ID. This is your clientID.
3. In index.html, change clientID to your OWN clientID.
4. You have to authorize your webpage to sign in via google. Go to https://console.developers.google.com/ -> Credentials
5. 2 things you need to do over here.<ol><li>Under OAuth Consent Screen -> Authorized Domains, key in your main web page without "/" or "https://". Examples are "codesandbox.io" and "bensjx.github.io".</li>  <li>Under Credentials -> "OAuth 2.0 client IDs", click "Web client (auto created by Google Service)". Now under Authorized Javascript Origins, enter the specific web page you want to authorize. Example: "https://10w5jv02vj.codesandbox.io".<br><i>Remember: codesandbox link change everytime you save your file so you have to keep repeating step ii everytime you change your code and save your file</i></li></ol>

## Note:

You MIGHT not be able to run this in codesandbox as you will receive a 'popup-closed-by user
error'. However if you refresh or use a new browser or clear your cache it might work again.<br>
Solution: Finish your code, commit to github, and run your web page using github hosted pages.
It should work from there

## Reference:

Type of data you can get from google login (e.g. email, name, id, family name) and might want to display:
https://developers.google.com/identity/sign-in/web/reference
