# Emmanuel Amoh — Technology Portfolio

A responsive multi-page personal technology portfolio built with HTML, CSS and vanilla JavaScript.

## Run locally
1. Extract this ZIP.
2. Open the extracted folder in Visual Studio Code.
3. Install the Live Server extension if you do not already have it.
4. Right-click `index.html` and select **Open with Live Server**.
5. Check the navigation and pages at desktop and mobile widths.

## Pages
Home, About, Skills, Projects, Certifications, Experience and Contact.

## Before publishing
- Confirm your exact job title and responsibilities at Fleeti.
- Replace the email placeholder in `contact.html`.
- Add your GitHub profile URL.
- Add certificate verification links where available.
- Add your CV only if you want it publicly accessible.
- Replace planned project descriptions with completed work and evidence.
- Verify every claim. Do not describe a certification as earned unless it has been awarded.

## Deploy using AWS Amplify Hosting
1. Create a GitHub repository, e.g. `emmanuel-amoh-portfolio`.
2. Push the contents of this folder to the repository root.
3. In the AWS Console, open AWS Amplify and choose **Create new app** → **Host web app**.
4. Connect GitHub and authorize access to the repository.
5. Select your repository and `main` branch.
6. For this plain HTML/CSS/JS site, use a static/no-build deployment configuration. The publish directory is the repository root; no framework build command is required.
7. Deploy and use the AWS-generated `amplifyapp.com` URL.
8. Test all seven pages and the mobile navigation.

## Architecture
Visitor browser → AWS Amplify Hosting (managed hosting and CDN delivery) → static HTML/CSS/JS assets.

## Cost and security
Amplify Hosting is usage-metered. Review current AWS pricing and your account's Free Tier eligibility before deployment. Configure an AWS Budget alert; it is a notification, not a hard spending cap. Never commit passwords, access keys, private documents or confidential employer information.
