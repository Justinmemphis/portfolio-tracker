Portfolio Tracker

01/28/2023:
- Organize pages for app
- Design sign up page
- Design header at top of remaining pages

Additional thoughts on security:
- Have positions grouped - but have groups with alphabetical input only - so no account numbers possible
- Have totals of groups show on page but not be stored in database
- database just has individual positions, not total
- disclaimer on front about positions not stored securely - not private, etc.

01/27/2023:
- Start design sketch in figma - design login page in figma

01/26/2023
- Created repo


Big picture:
- Manually input portfolio positions on certain date - and classify stock vs. bond
- Program runs update after market close to update position
- Every day the overall position of the portfolio is shown
- User authentication to save data
- Database of stock positions - update each close with position date

Design process:
- Create front-end sketch in figma
- Technologies to use - React, Node, MongoDB, 0auth
- Create backend shell (for secure authentication)
- Create react front-end - with react router
- Create stock API connection - need to get closing data for multiple positions
- Create database of stock positions - update after close
- Create classification for stock positions - or user input?
- Create user authentication
- Create databse of user stock positions - update position values at close

