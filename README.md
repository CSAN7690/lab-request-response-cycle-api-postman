# Request Response Cycle, APIs, and Postman Lab

You will be working with a free API of your choice for this lab.

## Getting Started

1. Choose an API that has no auth and no CORS from the following list: [public APIs](https://github.com/public-apis/public-apis)
1. Write your answers in this README.md file. Do not delete the questions. Write your answers after the `>`. If you need to write more than one paragraph, add more `>`.

## Instructions

Do your best to answer the questions with specific details when required fully. Writing about code clearly and thoroughly is a critical skill to practice. 

- Which one did you choose? Provide the name and base URL

> https://digimon-api.vercel.app

- What purpose is this API for (education/fun and games/information/etc.)?

> Provides information ℹ️ about digimon creatures 👾

- What is the URL of the documentation?

> http://digimon-api.vercel.app/index.html

- What is the full URL of one endpoint?

> http://digimon-api.vercel.app/api/digimon/name/wargreymon

- What is a sample of the data from the endpoint (copy and paste results from Postman, ok to shorten if it’s over 100 lines)? Be sure to wrap your answer in the correct formatting for code/JSON.

```json
[
    {
        "name": "WarGreymon",
        "img": "https://digimon.shadowsmith.com/img/wargreymon.jpg",
        "level": "Mega"
    }
]

```

- What status code did you get back?

> 200 OK

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `text/html; charset=iso-8859-1`

> `n/a`

- Summarize the most salient parts of the data you are getting back (for example, Cat facts returns JSON that identifies the source of the cat fact, the cat fact, information about when the fact was created and updated, and the fact itself).

> The summary of the data is ...

- How could you use this data in an application?

> I could imagine integrating this API into an game app that needs Digimon info 🤷

- What did you like about the documentation?

> The documentation was fairly straight-foward ⏤

- What did you find challenging about the documentation?

> There was no default key for expexted response headers so I had to manually look for them. 
>  Even then I could not find all the required info (content-length)

- Did the quality of the documentation impact your decision to use it?

> Not really because it did pique my nostaligic interest and it was nice to still see the img for certai digimon. ☺️

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> I stuck with the Digimon API for awhile but then experimented with the Yu-Gi-Oh API. Unfortunately that seemed like a lot to process 🙃

- In your own words, summarize the request-response cycle.

> The request-response cycle is a bit like sending a letter to a pen pal. You have a 'request' whether it is an update or info or questions and then place it in the envelope. After you send it out which should hopefully reach your friend. Once they open it (if its a good friend), they'll 'respond' by adressing your question.  After they place the letter in the envelope  and it's gone through it's journey across the world 🤔 it should reach you and hopefully received the desired response you wanted or needed. 

- In your own words, describe what an API is.

> An API is a messenger that allows different software apps to communicate and share info with each other.

- In your own words, describe the purpose of Postman.

> Postman is an application that helps novice developers like myself to test and interact with APIs. It's very much like a playground for me to play around 🙌🏽 with APIs and make sure they're working correctly 🫡
