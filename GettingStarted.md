# Getting Started 

## Step One - Sign in 
1. Sign in by clicking "Sign in" in the toolbar and entering your credentials. ![Sign in](./images/SignIn.png)
>NOTE: To edit metadata using the ANZLIC Metadata Tool, you will first need a user account with sufficient permission. If you do not have one, ask your administrator for help

## Step Two - Select a template
1. Under the **Contribute** option in the top toolbar and select **Add new record.** ![Add new record](./images/AddNew.png)
1. A new window will appear where you can find and select your starting template record. ![Template select](./images/TemplateSelect.png)
	1. Templates are stored by the types shown in the left hand column. **Dataset** templates will be shown by default.
	1. To select a template for **Service** metadata, select **Service** in the left had column
1. Select the desired template from the second column.
>NOTE: For default EMA installations, the **Emercency Management Dataset Template** should be used for dataset metadata. For service records, the **Emercency Management Service Template** should be used. Your administrator may see fit to provide variations of these templates for specific resource metadata.	
1. If you have membership in multiple groups, you ca select the appropriate group for this metadata record in the third column.
1. Clinking the green **Create** button in the forth column will launch your new metadata record in the _ANZLIC Editor_ window.

## Step Three - Edit Metadata Record
Opens in ICSM view
1. Work through the tabs from left to right
(insert image)
  1. General - General information about the resource
  1. Service - Special metadata related to services
  1. Contacts - Information about relevant parties to the resource or metadata
  1. Linage - Background and provenance information about the resource
  1. Keywords - Specific search terms by which the resource may be discovered
  1. Spatial - Includes metadata describing the resource location, reference systems used, and intended scale or resolution
  1. Constraints - The legal, security and other restrictions that may apply to the resource
  
Sidebar
* **Thumbnails & Distributions**
1. Link to an online resource
  1. Add a distribution
  1. Add a thumbnail
1. Link to a service or Link to a dataset if service metadata record

## Step Four - Validate and Save 
1. Click **Save Metadata** in the editor top menu.
1. Click the **Validate** button
	1. This checks the metadata record using XSD and Schematron validation
	1. A set of suggestions to correct any errors appears 
Follow GeoNetwork guidance

## Step 4a - Assign Category (Optional)
1. Click the **Categories** button in the editor top menu.
1. A list of of categories from which one _Should_ choose that braodly categorises the the resource. 
>NOTE: This is a GeoNetwork provided list that helps with the management of metadata records. The values are stored separately to the ISO19115-3 metadata record.

## Step 4b - Group (Optional)
1. If you wish to assign your metadata to a different group, click **Group** in the editor top menu.
>NOTE: You can only assign metadata to groups of which you are a member. Talk with your administraor for more help.

## Step 5 - Save and close
* Record is not published 
* Notify your reviewer that the metadata is ready for review.
	* This process may be automated if GeoNetwork workflow tools are enabled 
* Your adminstrator or reviewer will do this

### Workflow
To notify your reviewer that the metadata is ready for review and publishing, in the **Metadata view** for a selected record, select **Submit for review. ![Submit for review](./images/EditorMngRecord.png)

>NOTE: You may need first to **Enable workflow** by selecting that option under the same menu. ![Enable workflow](./images/EnableWorkflow.png)

A interface appears where you can add details to your review request. ![Submit for review](./images/Submission.png)]

The reviewers for your group will be notified that your metadata is ready to be reviewed and published.

## Getting Help
  This help document can be accessed in two ways:
  1. Select the **Need Help?* button at the bottom a side panel to open a directory of help pages in a new window,
  1. Clicking on most entry tools in the Edirot interface will provide a brief statement about the usage of that entry and a **Help** link to more information.
    >NOTE: **Tooltips** mst be enabled in the **View selector**for this behaviour.



# Navigating the Editing Window
1. (insert screenshot)
1. Describe header buttons (to be used after metadata is complete). Look to GN general help
    1. Categories
    1. Group
    1. Validate
    1. Cancel
    1. Save & close
    1. Save metadata
    1. View selector 
        1. (insert screenshot)
        1. Advanced
        1. XML
        1. More details (leave unchecked)
        1. Tooltips (make sure is checked to access inline help)
1. Main editing window
  1. Tabs
  1. Body
  1. Sidebar
        

## Tools and Notation
1. Mandatory elements are marked by a red asterisk
1. Help for specific elements is available by clicking on the element name or field (Tooltips **Must* be enabled)
1. Adding elements with the "+" button (image)
1. Deleting individual items - if a red X appears to the right of a line, this element may be deleted by clicking the red X
    1. Also applies to sections when allowed
1. Special interfaces
   1. Described in the inline help 
   1. insert links
1. Page navigation aids. Useful for longer more complex metadata and small screens where visibility of all elements is difficult.
  1. Collapsing and expanding sections is accomplished by clicking the caret at the left of the section name. 
	   1. Located in the upper left is a double caret in a blue circle. Clicking this collapses and expands all sections on a page.
	   1. The single caret in the blue circle on the lower left brings you to the top of the page.
	   1. Also on the lower left is a hamburger menu button in a blue circle. This exposes or hides the sidebar navigator. This consists of a list of all expandable sections in a page. Clicking a section in this sidebar takes one to that section.








