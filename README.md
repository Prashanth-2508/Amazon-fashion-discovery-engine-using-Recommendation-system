# Amazon-fashion-discovery-engine-using-Recommendation-system

## Problem statement :
Recommend the similar product/item/apparel in e-commerce based on Product discription and images.

## Data overview
tops_fashion.json (250MB file of all product data)
200 images (16k images file)

## Of these 19 features, we will be using only 7 features in this case-study.
1. asin ( Amazon standard identification number)
2. brand ( brand to which the product belongs to )
3. color ( Color information of apparel, it can contain many colors as a value ex: red and black stripes )
4. product_type_name (type of the apperal, ex: SHIRT/TSHIRT )
5. medium_image_url ( url of the image )
6. title (title of the product.)
7. formatted_price (price of the product)

## Procedure
- Implemented NLP technique (BoW, Tf-IDF, W2V) to convert the text features to numerical vectors.
- Calculated cosine distance between apparels and recommended top 20 apparels very similar to query item
