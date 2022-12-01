# Generating-Keywords-for-Google-Ads

Imagine working for a digital marketing agency, and the agency is approached by a massive online retailer of furniture. They want to test our skills at creating large campaigns for all of their website. We are tasked with creating a prototype set of keywords for search campaigns for their sofas section. The client says that they want us to generate keywords for the following products:

sofas
convertible sofas
love seats
recliners
sofa beds
The brief: The client is generally a low-cost retailer, offering many promotions and discounts. We will need to focus on such keywords. We will also need to move away from luxury keywords and topics, as we are targeting price-sensitive customers. Because we are going to be tight on budget, it would be good to focus on a tightly targeted set of keywords and make sure they are all set to exact and phrase match.

Based on the brief above we will first need to generate a list of words, that together with the products given above would make for good keywords. Here are some examples:

Products: sofas, recliners
Words: buy, prices
The resulting keywords: 'buy sofas', 'sofas buy', 'buy recliners', 'recliners buy', 'prices sofas', 'sofas prices', 'prices recliners', 'recliners prices'.

As a final result, we want to have a DataFrame that looks like this:

Campaign	Ad Group	Keyword	Criterion Type
Campaign1	AdGroup_1	keyword 1a	Exact
Campaign1	AdGroup_1	keyword 1a	Phrase
Campaign1	AdGroup_1	keyword 1b	Exact
Campaign1	AdGroup_1	keyword 1b	Phrase
Campaign1	AdGroup_2	keyword 2a	Exact
Campaign1	AdGroup_2	keyword 2a	Phrase

The first step is to come up with a list of words that users might use to express their desire in buying low-cost sofas.
