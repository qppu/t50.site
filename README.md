## GitHub Pages

To get a short and sleek subdomain for your own GitHub Pages site using **t50.site**, follow these 4 steps:

---

### Step 1

If you haven't already, log in to your GitHub account and set up your GitHub Pages site following  
https://pages.github.com  

**Make sure to add some reasonable content to your new page.**

---

### Step 2

Now determine your **t50.site** subdomain: either choose your username or the name of your repository according to the existing GitHub Pages URL.

For example, for:
http://foo.github.io/bar

yaml
Copy code

Either of the following would be possible:
foo.t50.site
bar.t50.site

yaml
Copy code

Guidance on choosing a suitable subdomain:  
https://github.com/iemabdullah/t50.site/wiki/Subdomain-Determination

---

### Step 3

#### If you're publishing from a branch
https://go.abdullah.nyc.mn/CHKDAp

Add a file named `CNAME` to your repository (in the `gh-pages` branch for project pages, or the branch set as your GitHub Pages source) with a **single line** matching your chosen domain.

Example:
foo.t50.site

yaml
Copy code

You may also configure the custom domain via **Repository Settings → Pages**.

---

#### If you're publishing using a workflow
https://go.abdullah.nyc.mn/WPZAeD

A `CNAME` file will **not** be processed when publishing via a workflow.

Instead:
- Go to **Repository Settings → Pages**
- Add your **t50.site** subdomain as a custom domain

Documentation:  
https://go.abdullah.nyc.mn/E3sizp

---

### Step 4

To finish the procedure, make a **pull request** in the relevant GitHub repository that adds your subdomain to the subdomains list.

Your new **t50.site** URL should go live within **24 hours**.  
Keep an eye on your pull request in case of naming conflicts or requested changes.

---

## Other Providers

If you'd like to use **t50.site** for a website hosted elsewhere, you can do that too.

---

### Step 1

Set up your site with any hosting provider you prefer.  
The hosting provider must support **custom domains via a CNAME DNS record**.

---

### Step 2

Choose your **t50.site** subdomain based on your username or project name.

Example:
foo.t50.site

yaml
Copy code

Subdomain selection guidance:  
https://github.com/iemabdullah/t50.site/wiki/Subdomain-Determination

---

### Step 3

Follow your hosting provider’s instructions to add **t50.site** as a custom domain.

A list of commonly used hosting providers and configuration notes:  
https://github.com/iemabdullah/t50.site/wiki/3rd-party-hosts

---

### Step 4

Submit a pull request to register your **t50.site** subdomain.

---

## Content Requirements

> [!IMPORTANT]
> The following rules apply to websites hosted on **t50.site** subdomains:
>
> **Websites must be directly related to the ecosystem or community**  
> (e.g. JavaScript tools, libraries, frameworks — not personal pages or portfolios)
>
> - No placeholder pages  
> - Websites must contain meaningful, relevant content  
> - No automatic redirects away from the **t50.site** domain  
> - Redirects must require user interaction  
> - No unrelated or misleading content  
> - Content must stay focused on its intended purpose
>
> Please also review the full Terms and Conditions of the service.

---

## Acknowledgements

Thanks to **Cloudflare** for providing the DNS infrastructure that makes **t50.site*
