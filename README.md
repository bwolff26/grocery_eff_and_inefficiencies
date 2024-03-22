# grocery_eff_and_inefficiencies

## Problem Statement

The vast majority of the time, grocery shopping is not cathartic but carcenogic, prompting one to get only more grey hairs with having to go back and fourth from isle to isle and by the time you check out your ice cream has turned into soup.

Based upon a project I did in VBA year or so ago, I already wrote code to, given a user-inputted grocery list (defaults provided from a pre-existing database), provide the most efficient way to go get all of your items as quickly as possible, tiering cold items at the very end. However, besides just wanting another pactical excuse to work on my Python, I noticed a number of inefficiencies:
1) Maybe we only have a few cold items, so have an override?
1b) Maybe an item is in an akward place, so have an override?
2) Maybe the doors change positions?
3) Maybe you start shopping at a new store?

With these questions and more, particularly 3, I strive to make a more flexible efficient grocery list. In truth, I question how far we'll be able to go with 3, as likely that can't be formmulaic definition by forever user inputted (even scrapping store locations would count as that in my book, although that'd still be an upgrade).

## Additionally

After thinking about this, I might as well take the time to analyze cost efficiency: So much of one's bill is for food. But can we minimize it? Are there not solutions, whether brothers from a more expensive and 'better' brand to a cheaper and 'gross' one to cousins such as subsituting lemons for limes (will try to think of a better example later, hopefully), to bring the costs down? Likely this part of the project would call to use some API to get a giant list of alternatives.