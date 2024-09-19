# 1️⃣ | Getting Started


Thie instructions are for participants of the instructor-led **"WRK550: Build a Retail Copilot Code-First on Azure AI"** workshop offered on the Microsoft AI Tour (2024-2025). If you're not at an AI Tour event right now, you can register for an upcoming event in a city near you.

- [**Register to attend**](https://aitour.microsoft.com/) at a tour stop near you.
- [**View Lab resources**](https://aka.ms/aitour/wrk550) to continue your journey.

!!! info "First → Review [ 0️⃣ | Pre-requisites](./../00-Before-You-Begin/index.md) before you begin setup"

## 1. Launch Skillable Lab

Your instructor should have shared a _Skillable Lab Link_ with you at this time. In this section, we'll launch the Skillable VM and verify that we have the right credentials for the workshop. 


??? note "Step 0: Launch Browser Window In Incognito Mode"

    The workshop is conducted completely within a browser environment. You may have an enterprise Azure or GitHub account that you are logged into that may cause conflicts. To avoid this, we recommend opening a new browser window in **incognito mode** (private mode) with your preferred browser. 

    - Open a new browser window in incognito or private mode
    - **Tip**: If you're using Microsoft Edge, we recommend creating 2 tab groups as follows:
        - Group 1 = **"Skillable"** - open tabs A and B below for Skillable setup
        - Group 2 = **"Development"** - open tabs 1️⃣-4️⃣ below for all workshop development

??? note "Step 1: Launch Skillable Lab"

    1. Open a new browser window (in incognito mode)
    1. Navigate to Skillable Lab (**use insrtuctor provided link**) = Tab A 
    1. Click `Launch` - opens window with Login, Instructions = Tab B
    1. Click `Resources` tab - find admin `Password`
    1. Click to fill password for login - confirm
    1. You should see: Windows 11 Desktop ✅
    1. Revisit `Resources` tab - look for `Azure Portal` section
    1. Verify `Subscription`, `Username`, `Password` assigned ✅
    1. Keep this browser open - you will need the credentials in the next step

    **🌟 | CONGRATULATIONS!** - Your Skillable VM is live!


## 2. Set up your development environment

??? note "Step 2: Open GitHub in tab 1️⃣, Launch Codespaces in tab 2️⃣"

GitHub Codespaces will be our development environment for this workshop. You will need to log into your own GitHub account and copy (fork) the workshop materials to your account. Let's do that now.

1. **Open a new browser window** on your laptop. 

1. **Click the link** below to your clipboard: 
    * `https://github.com/Azure-Samples/contoso-chat`

1. **Paste the link in your browser** to open the GitHub repository.

1. **Sign in to GitHub** if you aren't logged in already, using your own GitHub account credentials.

1. Click **Fork** in the top-right corner of the page

1. In the "Create a new fork" page, scroll down and **uncheck** the option "Copy the main branch only".

   * **Important**: If you forget to uncheck that option, you will need to delete your fork and try again. 

1. Click the **Create Fork** button.

   * You should now be at the page `https://github.com/YOURUSERNAME/contoso-chat` within your own GitHub account, in a single browser tab (Tab 1️⃣).
   
   * You now have a copy (known as a fork) of this workshop repository in your own GitHub account! Feel free to play with it, you won't break anything.

1. Use the branch selection drop-down on the left side that now reads **main** and select the branch **aitour-WRK550**.

1. Click the green **<> Code** button in the top-right part of the page, click the **Codespaces** tab, and then click **Create codespace on aitour-WRK550**. This will open a new Codespaces window in Tab 2️⃣.

1. This step takes a few minutes. The instructor will give you an overview of the session, and then you can begin work on your own in the Codespaces environment in your browser when it's ready.

    **🌟 | CONGRATULATIONS!** - Your Codespaces is running

## 3. Take a look at your resources in the Azure Portal

??? note "Step 3: Load tge Azure Portal in tab 3️⃣"

    1. Open a new browser tab = Tab 3️⃣
    1. Navigate to the [Azure Portal](https://portal.azure.com)
    1. Sign in with Skillable `Username`-`Password` from Step 1.
    1. Click `Resource Groups` - refresh it periodically if needed
    1. See: resource group `rg-AITOUR` created ✅
    1. Click resource group item - see 'Overview' in details page
    1. View `Deployments` under **Essentials** - see 35 deployments ✅
    1. View `Overview` resources listed - veriify 15 resources created ✅

    **🌟 | CONGRATULATIONS!** - Your Azure Infra is Provisioned!

??? note "Step 4: View Azure AI Studio in tab 4️⃣"

    1. Open a new browser tab = Tab 4️⃣
    1. Navigate to the [Azure AI Studio](https://ai.azure.com)
    1. Click `Sign in` - should auto-login with Azure credentials
    1. Click `All resources` - see: a hub resource listed
    1. Click hub resource - see: a project resource listed
    1. Click `Deployments` tab - see: 4 models under `aoai-connection` ✅
    1. Check: `gpt-4`, `gpt-35-turbo`, `text-embedding-ada-002` listed ✅

    **🌟 | CONGRATULATIONS!** - Your Azure AI Project was created!

??? note "Step 5: View Container Apps Endpoint in tab 5️⃣"

    1. Return to Azure Portal = Tab 3️⃣
    1. Visit the `rg-AITOUR` Resource group page
    1. Click the `Container Apps` resource - see details page
    1. Look for `Application Url` - at top right
    1. Click to launch in new tab = Tab 5️⃣
    1. See: page with `"Azure Container Apps"` and logo

    **🌟 | CONGRATULATIONS!** - Your ACA Endpoint is alive!


We verified our Skillable credentials worked, and launched our Codespaces environment!

---

!!! info "Next → 2️⃣ [Validate Setup](./02-validate.md) before you begin building"
