Grocery Single-Tab Redirector

This is a lightweight web app (redirector.html) that makes it easier to search groceries across Fry’s, Safeway, and Target using a single input box. It’s designed to work smoothly on iPad Safari (and other modern browsers) where opening multiple tabs is necessary.

⸻

✨ Features
	•	Single search bar → Type once, update all three sites.
	•	Single-session tabs → Only three tabs are ever opened. Each new search updates those same tabs (instead of opening new ones).
	•	Custom base URLs → Override the default Fry’s, Safeway, or Target search URLs if needed.
	•	ZIP support → Optionally specify a ZIP code (most retailer sites use cookies to remember your chosen store).
	•	Local persistence → Remembers your last query, ZIP, and custom URLs using localStorage.

⸻

🚀 How it works
	1.	Open [redirector](https://smarcotte4g.github.io/GroceryFinder/redirector.html) in Safari (or your browser of choice).
	2.	Click Start session → This will open three tabs:
	•	Fry’s
	•	Safeway
	•	Target
	3.	Type your grocery item in the search bar and click Search →
The existing three tabs will update with the new query.
	4.	Repeat searches as needed — no new tabs are opened.

⸻

🛠️ Options
	•	ZIP code (optional): Helps some retailer sites tailor store availability.
	•	Custom base URLs (optional):
You can provide alternate search URLs if the defaults don’t work.
Defaults are:
	•	Fry’s: https://www.frysfood.com/search
	•	Safeway: https://www.safeway.com/shop/search-results.html
	•	Target: https://www.target.com/s

⸻

⚙️ Technical Notes
	•	Uses vanilla JS and Tailwind CSS for styling.
	•	Relies on window.open references to keep track of the three retailer tabs.
	•	Works around iOS/iPadOS tab restrictions by requiring a user gesture (clicking Start session) to open the tabs once.

⸻

📦 Usage

Just open redirector.html in a browser — no server setup required.
For iPad users:
	1.	Add redirector.html to your home screen or bookmarks.
	2.	Tap Start session once per shopping trip.
	3.	Use the search bar to update your three tabs without cluttering Safari.

⸻

