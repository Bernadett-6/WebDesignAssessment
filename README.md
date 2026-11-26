# Aetherium Nails

github repo link:

https://github.com/Bernadett-6/WebDesignAssessment

hosted-page link:



## Website goal

For my web design assessment I choose to do a nail appoitment booking website for a salon. The user is a client making an appointment or just checking out information about the salon like treatments,reviews or prices.

### Table of contents:

- Home page
- Book Now
- Pricelist

For inspiration I looked at other salon's websites in dublin like:

https://www.dublinnails.com/
https://sugardolls.ie/
https://duchess.ie/
https://www.tropicalpopical.com/

 I wanted to get a feel for what common elements a user who is using these websites would want to find and to make sure I include them in my own website. I concluded that the home page should have loads of pictures, have the book now button be very obvious as soon as you're on the home page and prices/treatments, reviews and location options were very important to have too. The pictures I ended up using were my own work i have done over the years.

To aid me in the development i have used ChatGPT to speed up the process, i have made it generate the skeleton of my website for all my pages, this has helped to save time and be more efficient.

https://chatgpt.com/share/6af9b299-1e34-83eb-9cbc-ce25f1a2c912

https://chatgpt.com/share/6afe0d62-77a0-83ed-b375-b3bf1150e787

https://chatgpt.com/share/6b034a12-f820-83eb-8365-ff94ad9177df

https://chatgpt.com/share/6b0876d8-0ae4-83eb-bf5f-f2e945ff6355

## HTML & CSS

Throughout the project i have used bootstrap and my own css to style the website. Here im using my own class names ( pricelistPage, itemPrice, etc.) in combination with bootstrap's grid system of containers,rows,columns this way it's easy to organize content and helps make the layout responsive to smaller screens while still being able to add other design choices like a gradient background that I wouldnt be able to achieve with just bootstrap.

```
 <body class="pricelistPage">

    <div class="container">
      <div class="row">

        <div class="col-md-6">
          <div class="px-4 border rounded mx-2 my-5" style="max-width: 700px">
            <h2 class="p-4 priceListheading">Pricelist</h2>

            <div class="mb-5 itemPrice">
              <span>Acrylic</span>
              <span class="dots"></span>
              <span class="price">€60</span>
            </div>
```

```
.formPage,
.pricelistPage {
    background-image: linear-gradient(to top, black, #252B63);
    min-height: 100vh;
}

.itemPrice {
    display: flex;
    align-items: baseline;
    gap: 10px;
    margin-bottom: 15px;
}

.dots {
    flex: 1;
    border-bottom: 2px dotted white;
}

.price {
    white-space: nowrap;
}
```

