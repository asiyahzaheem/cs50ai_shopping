# cs50ai_shopping
The 1st Learning project of CS50's AI with Python.

When users are shopping online, not all will end up purchasing something. Most visitors to an online shopping website, in fact, likely don’t end up going through with a purchase during that web browsing session. It might be useful, though, for a shopping website to be able to predict whether a user intends to make a purchase or not: perhaps displaying different content to the user, like showing the user a discount offer if the website believes the user isn’t planning to complete the purchase. How could a website determine a user’s purchasing intent? That’s where machine learning will come in.

This project builds a nearest-neighbor classifier to solve this problem. Given information about a user — how many pages they’ve visited, whether they’re shopping on a weekend, what web browser they’re using, etc. — the classifier will predict whether or not the user will make a purchase. The classifier won’t be perfectly accurate — perfectly modeling human behavior is a task well beyond the scope of the course — but it should be better than guessing randomly. To train the classifier, a CSV file is used that contains some data from a shopping website from about 12,000 users sessions.


