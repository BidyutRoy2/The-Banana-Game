# The Banana Game Auto Click Script

💠The script is randomly auto-clicking the Banana App

💠The script is available on PC & Mobiles

🟩 Register: https://t.me/OfficialBananaBot/banana?startapp=referral=P2E0J5

💠Script. Both Platforms [PC & Android] 

💠Right-click on the app

💠Select "Inspect"

💠Switch to the "Console" tab.

💠Select "Banana..."

💠Enter the code below or copy

💠Press `Enter`

<p align="center">
<img src='imageI.png' style="width:400px;height:600px;">
</p>

# Copy Code & Enter `Inspect` `Console`

```bash

const bananaElement = document.querySelector('.banana-image');

// Function to generate random coordinates within the element
function getRandomCoordinates(element) {
  const rect = element.getBoundingClientRect();
  const x = Math.random() * (rect.right - rect.left) + rect.left;
  const y = Math.random() * (rect.bottom - rect.top) + rect.top;
  return { x, y };
}

// Function to get the current and max click values
function getAvailableClicks() {
  const currentClicks = parseInt(document.querySelector('.value').innerText.split('/')[0], 10);
  const maxClicks = parseInt(document.querySelector('.value').innerText.split('/')[1], 10);
  return { currentClicks, maxClicks };
}

// Function to click at random times with adjustable speed
function randomClick(minDelay, maxDelay) {
  const { currentClicks, maxClicks } = getAvailableClicks();

  if (currentClicks < maxClicks) {
    // Get random coordinates within the banana element
    const { x, y } = getRandomCoordinates(bananaElement);

    // Create the click event at the random coordinates
    const clickEvent = new MouseEvent('click', {
      bubbles: true,
      cancelable: true,
      view: window,
      clientX: x,
      clientY: y
    });

    // Dispatch the click event
    bananaElement.dispatchEvent(clickEvent);

    console.log(`Clicked at: (${x}, ${y})`);

    // Set a random delay for the next click between minDelay and maxDelay
    const randomDelay = Math.random() * (maxDelay - minDelay) + minDelay;
    setTimeout(() => randomClick(minDelay, maxDelay), randomDelay);
  } else {
    console.log("No more clicks available!");
  }
}

// Start the random click process with speed control
// Example: 100ms (0.1s) to 300ms (0.3s) delay between clicks 
randomClick(100, 300);

```


# ▄︻デ𝙂𝙚𝙩 𝙇𝙖𝙩𝙚𝙨𝙩 𝘼𝙞𝙧𝙙𝙧𝙤𝙥𝙨 & 𝙐𝙥𝙙𝙖𝙩𝙚𝙨═━一

### ▄︻デ𝙅𝙤𝙞𝙣 𝙏𝙚𝙡𝙚𝙜𝙧𝙖𝙢═━一 [🎀  𝐻𝒾𝒹𝒹𝑒𝓃 𝒢𝑒𝓂  🎀](https://t.me/hiddengemnews) 

### ░▒▓█►─═  𝓗𝓲𝒹ᗪ𝓔η Ǥέ𝕄 ═─◄█▓▒░
