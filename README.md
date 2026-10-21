# Ballot Calculator

A simple, large-print calculator for the **Register of Official Ballots for Early Voting at Branch Location** form.

Poll workers type whole numbers into lines 1 to 4:

1. Number of ballots voted in person (voters on the ePollBook)
2. Number of spoiled ballots (voided)
3. Number of provisional ballots voted
4. Number of unused ballot paper (unsigned and unstamped)

Line 5, shown in blue, adds them up as you type. It should equal the total number of ballot paper received at the Vote Center.

## Use it

Open `index.html` in any web browser. There is nothing to install. It also works when hosted on GitHub Pages.

## Designed for everyone

- Large text and high contrast, with light and dark modes
- Big boxes and buttons that are easy to tap
- Phones and tablets show the number keypad
- Only whole numbers are accepted; decimals, minus signs and letters are refused with a friendly note
- Press Enter to move to the next box
- "Clear all boxes" with an Undo button in case it was tapped by mistake

## Put it on an iPhone or iPad home screen

1. Open the page in Safari.
2. Tap the Share button, then **Add to Home Screen**.
3. Tap **Add**. The calculator now opens full screen from its own blue icon, like an app.

On Android, open it in Chrome and choose **Add to Home screen** (or **Install app**) from the menu.

The page needs to be served over HTTPS for this, for example with GitHub Pages
(Settings → Pages → Deploy from branch → `main`, root folder).
