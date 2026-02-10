## Bug ID
BR-001

## Title
Rooms number changes automatically without user notification

## Environment
- Website: Booking.com
- Browser: Chrome
- OS: Windows 10

## Preconditions
- User is on Booking.com homepage

## Steps to Reproduce
1. Enter a valid destination
2. Select dates
3. Select 1 adult
4. Select 3 rooms

## Actual Result
- The system automatically changes the number of adults without notifying the user

## Expected Result
- The system should either prevent selecting more rooms than adults or display a clear message explaining the adjustment

## Severity
Medium

## Priority
Medium


----


## Bug ID
BR-002

## Title
Currency change is not applied consistently across pages

## Environment
- Website: Booking.com
- Browser: Chrome
- OS: Windows 10

## Preconditions
- User is on Booking.com homepage
- Internet connection is available

## Steps to Reproduce
1. Enter "Islandia" in the destination field
2. Select check-in date: 10/03/2026
3. Select check-out date: 20/03/2026
4. Select 1 adult
5. Click on the "Search" button
6. Open one accommodation from the search results (opens in a new tab)
7. In the accommodation page, change the currency

## Actual Result
- Different pages display different currencies at the same time (search results page and accommodation page)

## Expected Result
- The selected currency should be applied consistently across all pages and tabs during the user session
 
## Severity
Medium

## Priority
Medium
