# Functional test-cases L4

## General preconditions

- Website [https://www.tesla.com](https://www.tesla.com) is opened;
- All possible popups are closed in such way, that all content on page is available.

# 1. Activating ZIP Code

## Preconditions

- Page “Custom Order” is opened

| ID | Test Step Description | Expected Result | Actual Result |
| --- | --- | --- | --- |
| 1 | Click button “Enter Delivery ZIP Code” | Pop-up window for entering ZIP Code has appeared  | Pop-up window for entering ZIP Code has appeared  |
| 2 | Enter digits to text field | Text “a valid zip code is required” disappeared when number of digits equals 5 | Text “a valid zip code is required” disappeared when number of digits equals 5 |
| 3 | Click button “Confirm” | Pop-up window has disappeared. The text “Enter Delivery ZIP Code” was replaced by the text “Delivery ZIP Code: xxxxx” with entered numbers in place of “xxxxx” | Pop-up window has disappeared. The text “Enter Delivery ZIP Code” was replaced by the text “Delivery ZIP Code: xxxxx” with entered numbers in place of “xxxxx” |

# 2. Checking price displaying

## Preconditions

- Page “Custom Order” is opened
- Button “Potential Savings” is clicked (by default)

| ID | Test Step Description | Expected Result | Actual Result |
| --- | --- | --- | --- |
| 1 | Click button “Purchase Price” | Price numbers under points “Rear-Wheel Drive” and “Dual Motor All-Wheel Drive” and information about shown prices are changed | Price numbers under points “Rear-Wheel Drive” and “Dual Motor All-Wheel Drive” and information about shown prices are changed |
| 2 | Click button “Potential Savings” | Price numbers under points “Rear-Wheel Drive” and “Dual Motor All-Wheel Drive” and information about shown prices are changed | Price numbers under points “Rear-Wheel Drive” and “Dual Motor All-Wheel Drive” and information about shown prices are changed |

# 3. Choosing car drive type

## Preconditions

- Page “Custom Order” is opened
- Button “Model 3” is clicked (by default)

| ID | Test Step Description | Expected Result | Actual Result |
| --- | --- | --- | --- |
| 1 | Click button “Model 3 Performance” | Picture of car has changed. Est. Delivery (estimated delivery) has been refreshed. Technical specifications have been refreshed. | Picture of car has changed. Est. Delivery (estimated delivery) has been refreshed. Technical specifications have been refreshed. |
| 2 | Click button “Model 3” | Picture of car has changed. Est. Delivery (estimated delivery) has been refreshed. Technical specifications have been refreshed. | Picture of car has changed. Est. Delivery (estimated delivery) has been refreshed. Technical specifications have been refreshed. |

# 4. Calling Feature Details

## Preconditions

- Page “Custom Order” is opened

| ID | Test Step Description | Expected Result | Actual Result |
| --- | --- | --- | --- |
| 1 | Click button “Feature Details” | Pop-up window with additional information has appeared. | Pop-up window with additional information has disappeared. |
| 2 | Click close button | Pop-up window with additional information has disappeared. | Pop-up window with additional information has disappeared. |

# 5. Listing Feature Details

## Preconditions

- Page “Custom Order” is opened
- Pop-up window with additional information (Feature details) is opened

| ID | Test Step Description | Expected Result | Actual Result |
| --- | --- | --- | --- |
| 1 | Move cursor to the right side of display | The button with a right arrow (if current card is non-last) has appeared. | The button with a right arrow (if current card is non-last) has appeared. |
| 2 | Move cursor to the left side of display | The button with a left arrow (if current card is non-first) has appeared. | The button with a left arrow (if current card is non-first) has appeared. |
| 3 | Click button with arrow | The card has changed to the corresponding neighboring one. Point under it has moved to corresponding position. | The card has changed to the corresponding neighboring one. Point under it has moved to corresponding position. |

# 6. Choosing color

## Preconditions

- Page “Custom Order” is opened

| ID | Test Step Description | Expected Result | Actual Result |
| --- | --- | --- | --- |
| 1 | Click color button | Picture of car has changed. Name of color and price under buttons have changed. | Picture of car has changed. Name of color and price under buttons have changed. |

# 7. Choosing wheels

## Preconditions

- Page “Custom Order” is opened

| ID | Test Step Description | Expected Result | Actual Result |
| --- | --- | --- | --- |
| 1 | Click wheel button | Picture of car has changed. Name of wheel, description and price under buttons have changed. | Picture of car has changed. Name of wheel, description and price under buttons have changed. |

# 8. Calling Additional Wheel Information

## Preconditions

- Page “Custom Order” is opened

| ID | Test Step Description | Expected Result | Actual Result |
| --- | --- | --- | --- |
| 1 | Click button “Learn More” | Pop-up window with additional information has appeared. | Pop-up window with additional information has appeared. |
| 2 | Click close button | Pop-up window with additional information has disappeared. | Pop-up window with additional information has disappeared. |

# 9. Choosing Interior

## Preconditions

- Page “Custom Order” is opened

| ID | Test Step Description | Expected Result | Actual Result |
| --- | --- | --- | --- |
| 1 | Click colored button | Picture of interior has changed. Name of interior and price under buttons have changed. | Picture of interior has changed. Name of interior and price under buttons have changed. |

# 10. Adding autopilot function

## Preconditions

- Page “Custom Order” is opened
- Button “Add” is not clicked (by default)

| ID | Test Step Description | Expected Result | Actual Result |
| --- | --- | --- | --- |
| 1 | Click button “Add” | Color of button has changed from white to blue.  Text of button has changed from “Add” to “Remove”. | Color of button has changed from white to blue.  Text of button has changed from “Add” to “Remove”. |
| 2 | Click button “Remove” | Color of button has changed from blue to white.  Text of button has changed from “Remove” to “Add”. | Color of button has changed from blue to white.  Text of button has changed from “Remove” to “Add”. |
