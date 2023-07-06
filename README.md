[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/6H2sAzcR)

<h1>Create Netlify Account and Deployment Project from GitHub 1️⃣</h1>
<ol>
<img src="img/ss%20(1).png">
<li>Creat a netlify account : if you don't hace a Netlify account, go to <a href="https://www.netlify.com/"> and sign up for a new account.</li>
<li>Create a New Site : once you have Netlify account, log in and create a new site by clicking on the "New site from Git" button </li>
<li>Configure the Deployment Settings : Choose your Git provider (GitHub, GitLab, etc) and select repository you forked earlier.</li>
<li>Deploy the Website: Click the "Deploy site" button in Netlify to start the deployment process. Netlify will build and deploy your website automatically. </li>
<li>Access the Deployed Website: Once the deployment is complete, Netlify will provide you with a unique URL for your deployed website. You can access your website by visiting this URL.</li>
</ol>

<h1>Buying a .site Domain at Niagahoster 2️⃣</h1>
<ol>
  <img src="img/ss%20(9).png">
<li>Visit the Niagahoster Website: Open a web browser and go to the Niagahoster website at https://www.niagahoster.co.id/.</li>
<li>Search for the Domain: On the Niagahoster homepage, you will find a search bar to check the availability of your desired .site domain. Enter your preferred domain name (without the extension) and select ".site" from the drop-down menu.</li>
<li>Check Availability: Click on the "Search" button to check the availability of the domain name you entered. Niagahoster will display the search results indicating whether the domain is available or not. If the domain is available, proceed to the next step.</li>
  <img src="img/ss%20(11).png">
<li>Review Your Order: You will be redirected to the shopping cart page, where you can review your domain order. Check the domain details, selected services, and the total price. If everything looks correct, click on the "Continue" button.</li>
<li>Choose Hosting or Proceed to Checkout: At this point, you have the option to either select a hosting package offered by Niagahoster or proceed directly to the checkout for purchasing the domain only. Make your selection based on your requirements.</li>
<li>Create an Account: If you don't have a Niagahoster account, you will need to create one. Click on the "Create Account" button and fill in the required information (name, email address, password). If you already have an account, log in using your credentials.</li>
<li>Complete the Order: Follow the on-screen instructions to complete the domain purchase. Provide the necessary billing information and select your preferred payment method (credit card, bank transfer, etc.).</li>
<li>Make the Payment: Follow the instructions to make the payment using your chosen payment method. Provide the necessary details and confirm the payment.</li>
<li>Domain Registration and Activation: After a successful payment, Niagahoster will initiate the domain registration process. This may take a few minutes to a couple of hours. Once the domain is registered and activated, you will receive a confirmation email with the details and next steps.</li>
</ol>

<h1>Steps to Connect Niagahoster Domain to Cloudflare and Configure DNS for Netlify Deployment 3️⃣</h1>
<ol>
<li>Sign in to Cloudflare: Visit https://www.cloudflare.com/ and sign in to your Cloudflare account.</li>
<li>Add a Site: After signing in, click on the "Add a Site" button in the Cloudflare dashboard. Enter your domain name and follow the instructions to add your domain to Cloudflare.</li>
<li>Change Nameservers: Once your domain is added to Cloudflare, Cloudflare will provide you with two nameservers. Copy the nameserver values provided by Cloudflare.</li>
<li>Log in to Niagahoster: Go to the Niagahoster website (https://www.niagahoster.co.id/) and log in to your account. Change Nameservers in the domain management settings, update the nameservers with the ones provided by Cloudflare. Save the changes.</li>
<li>Wait for Nameserver Propagation: It may take some time for the nameserver changes to propagate. This process typically takes a few minutes to a few hours. Be patient and wait for the changes to take effect. Return to Cloudflare once the nameserver changes have propagated, return to the Cloudflare dashboard.</li>
<li>Set Up DNS Records: After verifying the domain setup, navigate to the "DNS" tab in the Cloudflare dashboard. Here, you will add the necessary DNS records to connect your domain to the Netlify deployment.</li>
<li>Add CNAME Record: Create a CNAME record with the following settings:
<br>Name: Enter the desired subdomain or leave it blank for the root domain.
<br>Target/Value: Enter the Netlify subdomain for your deployment (e.g., your-netlify-subdomain.netlify.app).
<br>TTL: Select "Automatic" or set a suitable TTL value.
<br>Proxy Status: Enable the orange cloud to proxy the traffic through Cloudflare.</li>
<li>Save DNS Records: Save the DNS records you added in Cloudflare and Verify DNS Propagation: Wait for DNS</li>
</ol>

<h1>Result</h1>
<a href="https://hilmifauzi.site/">AND THIS IS THE SITE</a>
