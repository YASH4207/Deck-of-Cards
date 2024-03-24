Project Name- Deck of Cards
BaseURL- https://www.deckofcardsapi.com
Authorization- Not required


Collection Deck of Cards

Request 1 - GET Shuffle the Cards //api/deck/new/shuffle/?deck_count=1
	Raw Data - not required

Request 2 - GET  Draw a Card /api/deck/<<deck_id>>/draw/?count=2
  Raw Data - not required

Request 3 - GET Reshuffle the Cards /api/deck/<<deck_id>>/shuffle/?remaining=true 
  Raw Data - not required

Request 4 - GET A Brand New Deck /api/deck/new/
  Raw Data - Not required

Request 5 - GET A Partial Deck /api/deck/new/shuffle/?cards=AS,2S,KS,AD,2D,KD,AC,2C,KC,AH,2H,KH
  Raw Data - not required

Request 7 - GET  Shuffle Piles /api/deck/<<deck_id>>/pile/<<pile_name>>/shuffle/
  Raw Date - not required

Request 8 - GET  Listing Cards in Piles /api/deck/<<deck_id>>/pile/<<pile_name>>/list/
  Raw Date - not required
  
{Request 9 - GET  Drawing from Piles
https://www.deckofcardsapi.com/api/deck/<<deck_id>>/pile/<<pile_name>>/draw/?cards=AS 
https://www.deckofcardsapi.com/api/deck/<<deck_id>>/pile/<<pile_name>>/draw/?count=2
https://www.deckofcardsapi.com/api/deck/<<deck_id>>/draw/bottom/
https://www.deckofcardsapi.com/api/deck/<<deck_id>>/draw/random/
  Raw Date - not required}

Request 10 - GET  Returning cards to the deck:
https://www.deckofcardsapi.com/api/deck/<<deck_id>>/return/ copy
https://www.deckofcardsapi.com/api/deck/<<deck_id>>/pile/<<pile_name>>/return/
https://www.deckofcardsapi.com/api/deck/<<deck_id>>/return/?cards=AS,2S
https://www.deckofcardsapi.com/api/deck/<<deck_id>>/pile/<<pile_name>>/return/?cards=AS,2S
  Raw Date - not required
  
Request 11 - GET Back of Card Image /static/img/back.png
  Raw Date - not required
