# Test Cases – Booking.com

## TC-001 – Search hotel with valid data

**Preconditions:**
- User is on Booking.com homepage
- Internet connection is available
  
**Steps:**
1. Enter a valid destination: Baiona, Galicia
2. Select check-in and check-out dates: 28/2/2026 to 01/03/2026
3. Select 2 adults
4. Click on Search button

**Expected Result:**
- A list of available hotels is displayed

---

## TC-002 – Search hotel without destination

**Preconditions:**
- User is on Booking.com homepage

**Steps:**
1. Leave destination field empty
2. Select dates
3. Click on Search button

**Expected Result:**
- Error message is displayed: "Introduce un destino para empezar a buscar."
