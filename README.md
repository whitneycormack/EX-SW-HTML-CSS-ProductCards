#The Static Web HTML + CSS

##Setup

Run the following command in your terminal:

mkdir -p ~/workspace/exercises/static-web/productcards && cd $_
This will create a project folder and cd you into it.

###Instructions

Your task is to build a grid of cards for a company's products. Here are the requirements for the basic structure of the cards.

* Each card should be an article.
* Each card should take up 30% of the width of the browser window.
* Each product should contain a header element that, itself, contains an h2 element where the product's title will be written.
* Each product should have three sections:
  * 1. The first section should contain three child block elements.
        * The first element contains the product image.
        * The second element contains the product description.
        * The third element contains the product availability (e.g. "Available" or "Not Available")
  * 2. The second section contains product specifications.
        * This section should have a header containing the word "Specifications"
        * This section should contain two block elements
           * The first block element specifies the size.
           * The second block element specifies the weight.
        * This section should contain a footer.
            * The footer contains text stating when the product specifications become invalid.
  * 3. The third section contains the product pricing.
        * This section should contain a header.
        * This section should contain three block elements.
            * Each block element contains information about the price for different quantities.

Additional style requirements

* The entire card has a solid 1px border that is lightblue.
* The card title has a dotted 1px border that is lightgray.
* The title and product image are centered.
* Notice that the text for the description in the image is justified.
* The text for the product specification details and pricing details is bold.
* The availability element extends the full width of the card, with a dark grey background and yellow text.





