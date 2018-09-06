# September 5, 2018
## Snapshot 1.3

### New
- Hidden reporter information from copy and paste feature
- In the history card, Conclusion will replace Disposition
- Ability to add the middle name to the relationship payload
- The “Enter” button was disabled on the Search bar

### Changed
- No changes

### Fixed
- No fixes

## Facility Search and Profile 1.1
### New
- The Profile page will display the assigned worker Email address and Phone Number
- Allegations for complaints can now be seen in a facility profile
- The Profile page will display complaints from FAS for FFH/CFH/RFH originating in CWS/CMS
- The ability to filter for Active Facilities only
- Search no longer requires exact match for Facility Name nor Facility Address
  
### Changed
- No changes

### Fixed 
- The Complaint History field on profile page will now show N/A instead of No Data
- Facility name now exist in profile header and profile body making it easier to identify
- Lost Facilities During Replication Process – Fix was made to record the timestamp of information during the search process to ensure that data is loaded successfully
- The sort order for Children placed in home is now defaulted to Date of Placement
- The complaint history sort order is now sorted in order by, Open, Returned, Approved, Closed without Investigation


# July 11, 2018

## Identity Management 1.1
The purpose of this release is to introduce the functional user interface that will be the foundation for future user management.

### New
- User Detail Page
  - Ability to set user to Active/Inactive Status (status is for access to the CWS-CARES application)
  - Ability to assign Permissions to a user (permissions control what applications within CWS-CARES a user will be able to access)
  - Display of basic user information
- User List View (Able to select user from list to see User Details)
  - Display of users for an administrator filtered by County (County based on administrators county)
  - Ability to search for users (Search by Last Name)

### Changed
- Registration Email now calls out special instructions to ensure Copy/Paste of temp password is not attempted.

### Fixed
- No fixes

# June 21, 2018

##  Snapshot 1.2.1
### New
- No new features.
### Changed
- No changes.
### Fixed
- Fixed problem with “last change” jobs stalling when many records are updated on CWS/CMS.
- Fixed link to production release notes on the dashboard.

# June 08, 2018

##  Snapshot 1.2
Snapshot 1.2 will enable child welfare staff to search for clients in the child welfare system and see “at a glance” a view of their past involvement. This includes dates of referrals/cases, allegations, dispositions as well as victim and perpetrator information. The copy functionality will allow staff to copy and paste information into another document, such as an Investigative Narrative or Court Report.
### New 
- Log In using Cognito (See below)
- Placement Home as Address Type
- Attach Link in Relationship Card 
- Referral and Case Numbering
- Relationship Type Next to Parent’s Name
- Search By Middle Names and Suffixes
- Fuzzy and Phonetic Matches
- Sealed/Sensitive Authorization Error Message
### Changed
- Search by middle Initial and suffixes
- Single digit searches for date of birth
### Fixed
- Formatting changes on the snapshot
- Correction to user roles and permissions to view sensitive/sealed information 
- Enhanced system performance
- Syncing of CWS-CARES and CWS/CMS information
- View of address and telephone in search results and participant card
- Enhanced left hand navigation pane view 
- Alignment of cards and fields

## Facility Search 1.0
Facility Profile Search is an at-a-glance view that provides key information about a facility or home all on one screen! In CWS-CARES, facility and home data including contact information, license status, assigned worker and approved bed data is retrieved from CWS/CMS and Licensing Information System (LIS). Facility complaint information is retrieved from the Field Automation System (FAS). Additionally, staff can see the children placed in a facility or home, thereby eliminating the need to run a placement report.
### New 
-	Search for facilities or homes from CWS/CMS and LIS
-	View CWS/CMS child information associated with facilities or homes
-	Review complaint history from the FAS associated with facilities
-	Search on county, facility type, facility ID, facility name or facility address or any combination of these fields 
-	Search at the county or statewide level
### Changed
- No changes
### Fixed
- No fixes

## Identity Management 1.0
This introduces a new identity management system. 
### New
-	Ability to login to CWS-CARES securely without two factor authentication.
### Changed
- No changes
### Fixed
- No fixes

# March 16, 2017

##  Snapshot 1.1
### New
- User can logout of CARES
- Searching by Date of Birth will show matching results that are highlighted
- Displaying an error message to users based on privileges to view sensitive people information
- Users can view existing relationships for each person added to the snapshot/screening
- Users can see address types for people that they add to the screening/snapshot
- Users will see the option of using snapshot or screening in CARES
- Users will see a landing page for all digital services in CARES
- Users will see people added to the snapshot/screening in the side nav
- Users will see a side nav that will allow them to easily navigate in the app
- Users will be allowed or not be allowed to add people to the snapshot/screening based on their privileges.
### Changed
- Case history should not show unrelated minors case history. 
- Address and phone numbers to only show active (non-end dated) information
- The case history view to show familial sibling cases and parents (alleged, presumed, birth, etc)
- Search weighting results to elevate exact matches over partial matches
### Fixed
- Page content to scroll behind search results with ability to scroll just for people returned from search
- Phone number format in search results and people card
- Referrals in legacy can also be seen in CARES
- The latest referrals in legacy can also be seen in CARES
- Paste format of CWS history in Chrome browser
- Time out issue to stop users getting kicked out during an active session
- View of history that spans across counties. (privilege dependent)
- Phone number field to appear in expected format
- Mapping of Ethnicity to not show in Hispanic/Latino Origin field
- Photo placeholder to be responsive based on screen size.
- Search results to indicate the correct amount of visible results
- Search bar will not retain residual data from previous searches when switching between snapshot and screening. 
- Search results to show “no results” when the query doesn’t return results.
- User with sensitive privilege to add a person to a snapshot/screening with and see the person’s history from other counties. 
- User can search for a person with an apostrophe/hyphen in first or last name. 
- User can add people to a snapshot/screening and expect to see the same people’s existing relationships.
- Duplicated referral and case history should not show up in snapshot/screening
- JSON code should not be visible in CARES
- User will see accurate address for people added to snapshot/screening

# March 16, 2017

##  Snapshot 1.0
### New
- **Person Search**:  Added ability to search for clients by First Name, Last Name, Date of Birth, and Social Security Number.
### Changed
- No changes
### Fixed
- No fixes
