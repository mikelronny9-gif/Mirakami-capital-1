Murakami Capital Firebase package

Firebase project: murakami-capital
Admin email: yomawisdom55@gmail.com

This package uses Firebase Email/Password Authentication and Cloud Firestore for user profiles and admin synchronization. The dashboard is a demo/simulator; promotional credits are demo credit with no cash value.

Setup:
1. Create the admin account yomawisdom55@gmail.com in Firebase Authentication > Users.
2. Deploy firestore.rules to the Murakami Capital project.
3. Add/verify the GitHub Pages domain under Firebase Authentication > Settings > Authorized domains.
4. Register the web app under Firebase App Check with reCAPTCHA Enterprise, then put the site key into APP_CHECK_SITE_KEY in index.html. Test before enabling enforcement.
5. Firebase web configuration values are client-side configuration; access control is enforced through Firebase rules.
