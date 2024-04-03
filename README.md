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

## Conclusion

Copied from the end of the workbook:

Actually, let's go back a few steps:

Recall that we have two parts of the problem:

The first is maintaining/updating the list. Included in that is making sure no duplicate information gets put in, store is correct, etc.

The second is pulling from that whatever items currently desired.

@@@@@@@@@@@@@@@@@@@@@@

Honestly, the first part is ideal in Excel... yeah, potentially I could make something better, but it's like why bother...

Re. the second part - yeah,potentally a web-app would be better, ie something boss with streamlit that would let me show the list and manually click whatever I need then refresh, assuming it can even do something like that, but the effort...

Ie I'd like that more than the current 1 at a time in Excel, but it's like it aint broke... plus it forces me to go through each one.... Now, while albeit the current list is only needed for Jewel; oh, never mind - regardless of the format, that column would need to change to accomodate the current main grocery store that I go to...

So, unfortunately this project is being frozen indefinitely (4/3/24)... While I do find merit in completing it, I just have no motiviation to do so when my Excel/VBA version works fine. Plus, I'll still keep the minor victory of that somewhat complex zone-to-order conversion formula.