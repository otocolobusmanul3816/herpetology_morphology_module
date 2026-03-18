# Herpetology: Digital Morphology Laboratory

## Digital Morphology: Week 1
### Table of Contents
1. Instructions for creating an instance on the MorphoCloud
2. The repository housing our snake skull

To complete this project we will be using a software called 3D Slicer and utilizing the package SlicerMorph. 
<p align="center">
  <img src="https://raw.githubusercontent.com/SlicerMorph/SlicerMorph.github.io/refs/heads/master/husky_wide.png" width="400">
</p>

Learn more about [3DSlicer](https://slicermorph.github.io/) and [SlicerMorph](https://www.slicer.org/) on their website.

## MorphoCloud Set-up Instructions

MorphoCloud is an online repository for storing, sharing, and exploring 3D morphological datasets such as CT scans and surface models. It is closely integrated with 3D Slicer, allowing users to directly access and visualize datasets within the software for analysis and teaching.

---

### Step 1: Create the necessary accounts for the instance creation

#### GitHub Account

GitHub is a web-based platform for hosting and managing code using the version control system Git. It allows developers and researchers to store projects, track changes, collaborate with others, and share code publicly or privately. GitHub will be the platform on which our final project will primarily be stored.

- Create your user account here: https://github.com/

- When creating your account, use an email that you regularly check for messages.

- When prompted, you should also set up two-factor authentication. This can be done through the same application as all your USU accounts.

---

#### ORCID Account

ORCID (Open Researcher and Contributor ID) is a nonprofit organization that provides researchers with a unique digital identifier to distinguish them from other researchers with similar names. This identifier links a researcher to their publications, datasets, grants, and other scholarly work across platforms. We will not be using this directly, but it is required for creating an instance on the MorphoCloud.

- Create your user account here: https://orcid.org/signin

- When creating your account, I recommend selecting the sign-in through your institution option. Your **Organization** is *Utah State University*.

ORCID is essentially LinkedIn for academics and industry professionals. If you plan to continue conducting research, I would highly recommend getting your ORCID page started.

---

### Step 2: Request an instance from MorphoCloud

- Open the request form:  
  https://github.com/MorphoCloud/MorphoCloudInstances/issues/new?template=instance-request.yml

#### Fill out the form as follows:

- **Naming the instance:** Full Name USU Herpetology  
  *Example:* Lauren Houstoun USU Herpetology

- **Cloud Computing Instance Flavor:**  
  `g3.large - GPU instance (16 CPUs, 60 GB RAM and 50% of A100 GPU)`

- **Description:**  
  I am requesting an instance to be used in Utah State University’s Herpetology Course this semester. We will be using it for segmentation via MorphoDepot and for a larger comparative morphology project using 3D Slicer.

- **ORCID:**  
  Copy and paste your ORCID number here. This can be found on the top left of your ORCID page when you log in.

- **Email:**  
  Preferably use an email that is not your USU account. For some reason the USU emails have been deleting messages from this platform automatically.

- Then click **Create**

---

This will send a request to someone at MorphoCloud who will approve your request within 24 hours.

You will receive three emails right away corresponding to three chats that will appear in your GitHub instance (where your screen navigates after clicking **Create**). You can ignore these for now.

You should receive another email from GitHub when your request is approved. Once you receive that approval email, proceed to **Step 3**.

---

### Step 3: Create your instance

- Open the email you received and click the link to your instance request on GitHub.

- In the chat box at the bottom, type:
  ```
  /create
  ```

- Click **Comment**

This command tells GitHub to create your instance now that it has been approved.

---

#### Instance Creation Progress

This step will open a dialogue called **Instance Creation Progress**. Once all boxes show a green check, your instance is successfully online.

- This process can take **15–20 minutes**
- You do **not** need to keep the window open
- You will receive an email when the process is complete
- Timing depends on current server demand

---

### Final Step

Take a screenshot of your GitHub dialogue (including **muratmaga’s approval** and the **green checkmarks**) and submit it to the Canvas assignment.

## Digital Morphology: Week 2 & 3
### Table of Contents
1. The python code supporting the download of your species
2. 



