1. **Parse data into a custom struct:** You can create a typed Rust struct that holds movie data. This will make it easier to print the data and work with it further inside your program.
2. **Save data in a file:** Instead of printing out movie data, you can instead save it in a file.
3. **Create a [Client](https://docs.rs/reqwest/latest/reqwest/blocking/struct.Client.html) that logs into an IMDb account:** You might want IMDb to display movies according to your preferences before you parse them. For example, IMDb shows film titles in the language of the country you live in. If this is an issue, you will need to configure your IMDb preferences and then create a web scraper that can log in and scrape with preferences.

--------------------------
However, sometimes working with CSS selectors isn’t enough. You might need a more advanced solution that simulates actions taken by a real browser. In that case, you can use [thirtyfour](https://docs.rs/thirtyfour/latest/thirtyfour/), Rust’s UI testing library, for more powerful web scraping action.
