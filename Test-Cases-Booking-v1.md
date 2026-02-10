# Test Cases – Booking.com

## TC-001 – Search hotel with valid data.

**Preconditions:**
- User is on Booking.com homepage.
- Internet connection is available.
  
**Steps:**
1. Enter "Baiona, Galicia" in the destination field
2. Select check-in date: 28/02/2026
3. Select check-out date: 01/03/2026
4. Select 2 adults
5. Click on the "Search" button

**Expected Result:**
- A list of available hotels in Baiona, Galicia is displayed for the selected dates.

---

## TC-002 – Search hotel without destination.

**Preconditions:**
- User is on Booking.com homepage.
- Internet connection is available.

**Steps:**
1. Leave destination field empty
2. Select check-in date: 28/02/2026
3. Select check-out date: 01/03/2026
4. Click on the "Search" button

**Expected Result:**
- An error message is displayed indicating that a destination is required (e.g. "Enter a destination to start searching.").

---

## TC-003 – Search for a hotel with reversed dates.

**Preconditions:**
- User is on Booking.com homepage.
- Internet connection is available.

**Steps:**
1. Enter "Baiona, Galicia" in the destination field
2. Select check-in date: 01/03/2026
3. Attempt to select a check-out date earlier than the check-in date (e.g. 28/02/2026

**Expected Result:**
- The system does not allow selecting a check-out date earlier than the check-in date.

---

## TC-004 – Search hotel with children but without adults.

**Preconditions:**
- User is on Booking.com homepage.
- Internet connection is available.

**Steps:**
1. Enter "Baiona, Galicia" in the destination field
2. Select check-in date: 28/02/2026
3. Select check-out date: 03/03/2026
4. Select 1 child
5. Attempt to unselect all adults

**Expected Result:**
- The system does not allow searching without at least one adult selected.

---

## TC-005 - Apply breakfast included filter

**Preconditions:**
- User is on Booking.com homepage
- Internet connection is available

**Steps:**
1. Enter "Baiona, Galicia" in the destination field
2. Select check-in date: 28/02/2026
3. Select check-out date: 03/03/2026
4. Select 1 adult
5. Click on the "Search" button
6. Apply the "Breakfast included" filter

**Expected Result:**
- Only accommodations that include breakfast are displayed in the results list.

---

## TC-006 - Change currency to Argentine Peso.

**Preconditions:**
- User is on Booking.com homepage
- Internet connection is available

**Steps:**
1. Enter "Baiona, Galicia" in the destination field
2. Select check-in date: 28/02/2026
3. Select check-out date: 03/03/2026
4. Select 1 adult
5. Click on the "Search" button
6. Change currenci to "Argentine Peso (ARS)"

**Expected Result:**
- Prices are displayed in Argentine Pesos instead of Euros.

---

## TC-007 - Search for attractions in a selected location.

**Preconditions:**
- User is on Booking.com homepage
- Internet connection is available

**Steps:**
1. Enter "Vigo, Galicia" in the destination field
2. Select check-in date: 19/03/2026
3. Select check-out date: 20/03/2026
4. Click on the "Search" button
5. Navigate to the "Attractions" section

**Expected Result:**
- The system displays available attractions located in or near the selected destination.

---

## TC-008 - Select more rooms than adults.

**Preconditions:**
- User is on Booking.com homepage
- Internet connection is available

**Steps:**
1. Enter "Baiona, Galicia" in the destination field
2. Select check-in date: 28/02/2026
3. Select check-out date: 03/03/2026
4. Select 1 adult
5. Select 3 rooms
6. Click on the "Search" button

**Expected Result:**
- The system automatically adjusts the number of adults to match the number of selected rooms, or prevents selecting more rooms than adults.

