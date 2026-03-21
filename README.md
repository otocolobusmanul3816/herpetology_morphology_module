# Herpetology: Digital Morphology Laboratory

To complete this project we will be using a software called 3D Slicer and utilizing the package MorphoDepot. 
<p align="center">
  <img src="https://raw.githubusercontent.com/SlicerMorph/SlicerMorph.github.io/refs/heads/master/husky_wide.png" width="400">
</p>

Learn more about [3DSlicer](https://slicermorph.github.io/) and [SlicerMorph](https://www.slicer.org/) on their website.

## Table of Contents
   
### Digital Morphology: Week 1
  
<details>
<summary>MorphoCloud Set-up Instructions</summary>
  
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

</details>

<details>
<summary>MorphoDepot Set-up Instructions</summary>
  
## Setting up MorphoDepot

MorphoDepot is a web-based platform designed specifically for organizing, sharing, and collaboratively segmenting large volumetric datasets such as CT scans. It allows multiple users to work on and track segmentation progress in a centralized environment facilitated through GitHub.

<p align="center">
  <img src="https://github.com/MorphoCloud/SlicerMorphoDepot/blob/main/MorphoDepot.png" width="200">
</p>

Learn more about [MorphoDepot](https://github.com/MorphoCloud/SlicerMorphoDepot) on their GitHub repository. 

### Step 1: Activate your MorphoCloud Instance

Open the instance that you created before class in GitHub. The easiest way to find this is by going to your most recent email from the github-actions[bot]

In the chat box at the bottom type: /unshelve

Click ‘Comment’ 
- This will tell GitHub to unshelve your instance for three hours and send you an access code.

Open your email - you should receive an email from MorphoCloudPortal with your access information. 
- Click on the link for Web Connect
- Your username will be exouser
- Copy the Passphrase located under ‘Credentials’ in your email and paste it when prompted into the password window. 

### Step 2: Log in to your GitHub through the terminal

Open the terminal window on the left side of your screen. 
	
Copy and paste this command into the terminal: 

```
gh auth login
```
	
Push ‘enter’ on your keyboard to run the command line. 
- This will pop up with several command lines for you to answer before entering your login information. You may need to complete two-factor authentication, so keep your phone handy.

You have successfully completed your login process when you receive ‘Congratulations, you're all set!’ in your Firefox window and your terminal displays your account information.
- You can also verify this step by using this command in the terminal:

```
gh auth status
```

### Step 3: Creating an Issue

Navigate to the repository for the [Nerodia Segmentaiton Laboratory](https://github.com/otocolobusmanul3816/Nerodia_Segmentation_Laboratory)
	
In the top left corner, select the ‘Issues’ tab, then open a New Issue. 

The title should be your last name followed by the bone you were assigned. 


<details>
<summary>Student Bone Assignments (click to expand)</summary>

<table>
<tr>
  <td valign="top">

### Left (L)
| Student    | Bone Assignment |
|------------|----------------|
| Student 1  | Palatine       |
| Student 2  | Maxilla        |
| Student 3  | Prootic        |
| Student 4  | Dentary        |
| Student 5  | Quadrate       |
| Student 6  | Pterygoid      |
| Student 7  | Compound       |
| Student 8  | Ectopterygoid  |
| Student 9  | Prefrontal     |

  </td>
  <td valign="top">

### Right (R)
| Student    | Bone Assignment |
|------------|----------------|
| Student 10 | Palatine       |
| Student 11 | Prefrontal     |
| Student 12 | Pterygoid      |
| Student 13 | Prootic        |
| Student 14 | Quadrate       |
| Student 15 | Dentary        |
| Student 16 | Compound       |
| Student 17 | Ectopterygoid  |

  </td>
</tr>
<tr>
  <td valign="top">

### Both sides (L&R)
| Student    | Bone Assignment |
|------------|----------------|
| Student 18 | Supratemporal  |
| Student 19 | Angular        |
| Student 20 | Stapes         |
| Student 21 | Postorbital    |
| Student 22 | Splenial       |

  </td>
  <td valign="top">

### Paired Bones
| Student    | Bone Assignment |
|------------|----------------|
| Student 23 | Exoccipital    |
| Student 24 | Frontal        |
| Student 25 | Parabasisphenoid |
| Student 26 | Supraoccipital |
| Student 27 | Vomer          |
| Student 28 | Septomaxilla   |
| Student 29 | Premaxilla     |
| Student 30 | Nasal          |
| Student 31 | Parietal       |

  </td>
</tr>
</table>

</details>

The instructor will go through and assign the issues to you. Once your issue has been assigned, you can proceed to Step 4. 

### Step 4: Opening Files from MorphoDepot

Open 3D Slicer from the desktop of your instance. 

At the top of the window you will see a module list dropdown. Navigate to SlicerMorph → MorphoDepot.

<img src="https://github.com/Slicer/Slicer/releases/download/docs-resources/user_interface_module_toolbar.png" width="400">

You will get several dialogue boxes that ask about installing python codes and creating folders. Select ‘OK’ for all of these pop-ups. 

MorphoDepot will open a set of tabs on the left side of your screen: 
1. Configure:
   - Insert your GitHub username and email into the fields and hit ‘Apply’ 
2. Search:
   This is how you figure out if you loaded your GitHub information into the terminal correctly.
   - Select ‘Load Searchable Repository Data’
   - If this proceeds and pulls up a list of scans you can move on to the Annotate tab.
3. Annotate:
   - Select ‘Refresh GitHub’.
   - You should now see the issue that you created in the Assigned Issues box. Double-click on the issue, and allow 3D slicer to close the scene to open the file.
   - You will now be transported to the Segment Editor module.
  
### Step 5: Finding your boen and completing your segmentation

Switch to the Data Module via the module list dropdown.

Drag your file into the 3D window (blue) to visualize a 3D estimate representing the grey-scale values present in the slices.

<p align="center">
  <img src="https://github.com/Slicer/Slicer/releases/download/docs-resources/drag_to_view.gif" width="400">
</p>

<p align="center">
  *Image source: <a href="https://github.com/Slicer/Slicer/releases/download/docs-resources/drag_to_view.gif">Slicer Community, GitHub</a>*
</p>

For keyboard and mouse shortcuts useful for manipulating your data check out the [3DSlicer User Interface](https://slicer.readthedocs.io/en/latest/user_guide/user_interface.html)

Open the Markups Module via the module list dropdown. Remember, you can use the models on the [Blackburn Lab's ScetchFab](https://sketchfab.com/ufherps/collections/colors-of-skull-anatomy-938d312dab0c48f8960d5ed259883b21) to help locate your bones.

Select 'Point List' and place your point on your assigned bone in the 3D model. 

Expand the 'Control Points' drop down and right click on the table containing your point.

Select 'Jump Slices'. 
	- You should now see your point, and thus your bone, reflected in all four windows.

Switch back to the Segment Editor Module via the module list dropdown. 

We are going to begin the segmentation process by setting the threshold of greyscale values that are representative of our Region of Interest (ROI). Which in this case is bone. 

- Select the thresholding tool
	
<p align="center">
  <img src="https://github.com/Slicer/Slicer/releases/download/docs-resources/module_segmenteditor_threshold.png" width="50">
</p>

- Scroll down to find a blue adjustment bar. Adjust the bar so that only the white material (bone) in the red, green, and yellow windows are pulsing green.
- Once you are satisfied with your selection, click 'use for masking'.

You should now be automatically transported to the Paint tool. 

<p align="center">
  <img src="https://github.com/Slicer/Slicer/releases/download/docs-resources/module_segmenteditor_paint.png" width="50">
</p>

- Check 'Sphere brush'.
  	- We are now preparing to color in the bones in three demensions. It is important to note that when you are coloring in the bone you are not only coloring the current image but also those directly in front and behind your position. Make sure to scroll forwards and backwards while coloring to ensure that you are [1] staying in the lines and [2] capturing every aspect of your bone.

- Expand one of the slice windows.
  	- When selecting which window you want to expand, consider the shape of your bone. If you have a long bone, like the compound, you might not want to work from the red window (this window scrolls from nose to back of the skull). Rather, either the green (top to bottom) or yellow (left to right) windows would be more efficient because the distance you will need to travel will be shorter.
 
You can now color in the bone. If you get outside the lines in any one place you can toggle to the Erase tool. 

<p align="center">
  <img src="https://github.com/Slicer/Slicer/releases/download/docs-resources/module_segmenteditor_erase.png" width="50">
</p>

You can check your segmentation process by selecting 'Show 3D' and navigating to the blue window. 

Once you are done, we will need to name our segmentation and change the color of the bone.
	- Double-click on the segment that you have created and insert the name of the bone in the naming field. 
		- *Example*: Left Compound
	- Click to change the color next. 
		- Toggle from the Basic tab to Labels
		- Expand the drop-down and click on 'Files'
		- There will now be a color profile called "Jaimi Gray Tetrapod Skulls" for you to select. 
			- This does not have *every* tetrapod skull bone but it is fairly comprehensive. Find, or search for, your bone in the list and select the correct color. 

Now, you will need to submit your completed segmentation for your instructor to review. 

### Step 6: Submit your segmentation for review

Switch to the MorphoDepot Module via the module list dropdown. 
- You should still be in the Annotate tab of MorphoDepot.

In the Commit Message box, tell me a bit about your segmentation.
- What did you accomplish?
- What was the biggest challenge?

Then click, 'Commit and Push'. 

Finally, click 'Request PR Review'. 
- This will send your instructor a notification that you have completed and submitted the assignment. Your instructor will then open and review your submission. They may return for corrections if you made a major error (included the wrong bone, missed a large portion of your assigned bone, etc). 

</details>


## Digital Morphology: Week 2



