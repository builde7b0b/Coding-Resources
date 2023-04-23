# Here are the steps to link your GitHub Pages site to your Namecheap domain:

## Sign in to your Namecheap account and navigate to your domain's DNS settings.

## Create a new CNAME record with the following details:

Type: CNAME
Host: www
Value: yourgithubusername.github.io.
(Note: Replace "yourgithubusername" with your actual GitHub username.)
Save the changes and wait for them to propagate (this can take up to 48 hours).

## Go to your GitHub repository's settings and scroll down to the "GitHub Pages" section.

## In the "Custom domain" field, enter your domain name (e.g., www.example.com) and click "Save."

## Go back to your Namecheap account and add a new A record with the following details:

Type: A Record
Host: @
Value: 185.199.108.153
TTL: Automatic

### Repeat the previous step for the following IP addresses:
185.199.109.153
185.199.110.153
185.199.111.153

## Save the changes and wait for them to propagate (again, this can take up to 48 hours)
