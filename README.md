# Bills Tracking App.

[Bill Tracking App](https://blooming-badlands-45626.herokuapp.com/)

- Users can create their own accounts and login/logout
- Add bills: Amounts, date, and category by frequency (monthly/quarterly)
- View a list of all bills & bills total

## Features
- Create new user
- Edit user details
- Delete user
- Add bills
- List of bills
- Bills total
- Add bill categories by frequency
- Mark as paid or unpaid 
- Edit bill details
- Delete bill

## Features I Want to Add.
- Use paid/unpaid to view list of each
- Sorting options (view data in specified orders. Eg: by column)
- View graph of bills over time
- Monthly/Quarterly breakdown
- Comparisons with previous months/years
- Forecasting
- Splitting bills with other users


## Planning:
Rough Sketches:
- Page-map 
- Resources
- Page-layout


## Development:
- Started with building the user side first, and then the bills side.
- Step by step process. Incremental building and testing.


## Problems:
- Login - if name is spelled incorrectly page throws noMethod error
- Paid input - Currently not in use. Default value sent to params is on / nil. 
- Update bill - Unable to send query string via action??
- Adding fractional values to amount - SQL column value needs to be changed


## Lessons:
- Incremental development - Fail fast!
- Decide on naming conventions during planning. Naming conventions save lives.
- Using redirects to send query strings.
- Page throws error - Have you read the error correctly? No, but seriously, have you read the error correctly? No, but seriously, have you read the error correctly? No but seriously... If you're going round in circles, you havn't read the error correctly. 
- CSS "Templating" - Useful to apply css styling to elements accross a number of pages. This helps to maintain a coherent style across all pages and prevents having to go back and forth to check styling specs. 
- "Basic features" turn out to often not be so basic
![One does not simply...](/images/3fn5mu.jpg)