# User Interface Design Specification
## Chapter Overview
This document shows the user interface graphics specifications for the touchscreen on the customer pod. 

Topics in this chapter include:
- Top Section
	- Userlist section
    - User Registration section

## Top Section
Top section size is <w>x<h> 800x40 px and has a light blue background color
  
### Buttons
Button sizes are <w>x<h> 75x25 px and has white font colour on blue background color

### Icons
There is no icon in this section

### Layout
- Button for new user placed at far left,
- Check Box for hiding disabled users next to new user button
- Button for save user placed at far right

## User List Section
### Icons
Icons' size are <w>x<h> 14x14 pixels and are placed at top row of the User List section
The user list section has the following icons:
- Sorted icon
- Sort icon
- Filter Icon

#### Sorted Icon
The Sorted icon is used for user list section.
- File Formats: JPG, PNG
- File Name: sorted 
 
#### Sort Icon
The sort icon is used for user list section.
- File Formats: JPG, PNG
- File Name: sort
 
#### Filter Icon
The filter icon is used for user list section.
- File Formats: JPG, PNG
- File Name: filter

### Layout
- Head Row
	- ID Column: Text, sorted icon, filter Icon
	- UserName Column: Text, sort icon, filter icon
	- Email Column: Text, sort icon, filter icon
	- Enabled Column: Text, sort icon, filter icon
- Each Rows consist of user information as follows
	- ID, 
	- Username, 
	- Email
	- Enabler (true/false)
	- Each row’s background is lighter or darker depending on previous row’s background
- User Registration Section

### Icons
There is no icon in this section

### Layout
- Head Row
	- Title : New User, light but distinctive background color
- Username row
	- Username label
	- Textbox
- Display name row
	- Display Name label
	- Textbox
- Phone row
	- Phone label
	- Textbox
- Email row
	- Email label
	- Textbox
- User Roles row
	- Email label
	- Combobox
		- Guest, Admin, Superadmin
- Enabled row
	- Enabled Label
	- Chechbox
