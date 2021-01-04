# Awesome Fulcro

A curated list of awesome resources for [Fulcro](https://github.com/fulcrologic/fulcro) and [Fulcro RAD](https://github.com/fulcrologic/fulcro-rad), the most awesome (web)app framework the Earth has ever seen.

## Motivation

* [Why Build Solutions with Fulcro - Tom Toor](https://www.youtube.com/watch?v=PMbGhgVf9Do&t=628s) (video, 2019)
* [Want more from your frontend framework! Re-thinking web dev experience](https://blog.jakubholy.net/2020/talk-want-more-from-your-frontend-framework/) - "I will compare Redux + REST with a full-stack, component-centric solution based on a graph API (think GraphQL) that I came to love."

## Learning

### Official and semi-official documentation

* [Fulcro Developers Guide](https://book.fulcrologic.com/)
* [Fulcro 3 tutorials (video)](https://www.youtube.com/playlist?list=PLVi9lDx-4C_T7jkihlQflyqGqU4xVtsfi) indispensable!
   * Alex Eeberts [Fulcro Video Notes](https://github.com/aeberts/fulcro-notes-public) provide a detailed table of contents for the videos, with links to the corresponding sections
* [All Tony Kay's videos](https://www.youtube.com/c/TonyKayNW/videos)
* [Fulcro RAD Developer’s Guide](https://book.fulcrologic.com/RAD.html)
* [Pathom v2](https://blog.wsscode.com/pathom/v2/pathom/2.2.0/introduction.html)
* 2020 podcast series on Fulcro and Pathom is also a very valuable resource, full of insights and valuable reasoning
  - [S4 E6 - Fulcro with Tony Kay (Part 1)](https://soundcloud.com/user-959992602/s4-e6-fulcro-with-tony-kay-part-1)
  - [S4 E7 - Fulcro with Tony Kay (Part 2)](https://soundcloud.com/user-959992602/s4-e7-fulcro-with-tony-kay-part-2)
  - [S4 E8 - Fulcro with Tony Kay (Part 3)](https://soundcloud.com/user-959992602/s4-e8-fulcro-with-tony-kay-part-3)
  - [S4 E9 - Fulcro with Tony Kay (Part 4)](https://soundcloud.com/user-959992602/s4-e9-fulcro-with-tony-kay-part-4)
  - [S4 E10 - Fulcro with Tony Kay (Part 5)](https://soundcloud.com/user-959992602/s4-e10-fulcro-rad-and-guardrails-with-tony-kay-part-5)
  - [S4 E15 Pathom with Wilker Lúcio (Part 1)](https://soundcloud.com/user-959992602/s4-e15-pathom-with-wilker-lucio-part-1)
  - [S4 E16 Pathom with Wilker Lúcio (Part 2)](https://soundcloud.com/user-959992602/s4-e16-pathom-with-wilker-lucio-part-2) 

### Tutorials

* https://awkay.github.io/om-tutorial/#!/om_tutorial.D_Queries - this older OMNext / Eql tutorial is reportedly useful for understanding query syntax
* Chris O'Donnell's Gift list dev diary series (2020) - building a non-trivial Fulcro app from scratch, step by step
    1. [introduction](https://chrisodonnell.dev/posts/giftlist/intro/)
    1. [authentication](https://chrisodonnell.dev/posts/giftlist/authentication/)
    1. [routing](https://chrisodonnell.dev/posts/giftlist/routing/)
    1. [initial backend](https://chrisodonnell.dev/posts/giftlist/initial_backend/)
    1. [backend persistence](https://chrisodonnell.dev/posts/giftlist/backend_persistence/)
    1. [parser tests](https://chrisodonnell.dev/posts/giftlist/parser_tests/)
    1. [API auth](https://chrisodonnell.dev/posts/giftlist/api_auth/)
    1. [form and listing](https://chrisodonnell.dev/posts/giftlist/gift_list_form/)
    1. [navigation](https://chrisodonnell.dev/posts/giftlist/gift_list_navigation/)
    1. [deployment](https://chrisodonnell.dev/posts/giftlist/deployment/)
* [Fulcro via Re-frame](https://folcon.github.io/post/fulcro-basics/2020-05-12-Fulcro-via-re-frame/) — makes a couple of comparisons to re-frame and proceeds to the Fulcro basics: defsc, queries, idents, normalization, mutations, and targeting.

### Other

* [EQL Style Guide](https://github.com/souenzzo/eql-style-guide) - Some tips about how to model, name, and organize your domain and your data.
* [Fulcro Troubleshooting Decision Tree](https://blog.jakubholy.net/2020/troubleshooting-fulcro/) - A decision tree to help you go from a problem to the most appropriate troubleshooting steps
* [Fulcro Explained: When UI Components and Data Entities Diverge](https://blog.jakubholy.net/2020/fulcro-divergent-ui-data/) - "Fulcro’s stateful components serve normally both as elements of the UI and to define the data model, i.e. data entities with their unique IDs and attributes. But what if your UI and data model needs diverge? We will take a look at what different kinds of divergence between the UI and data entities you might encounter and how to solve them."
* [Error handling in Fulcro: 3 approaches](https://blog.jakubholy.net/2020/error-handling-in-fulcro/)
* [Fulcro notes on Tony Kay video series](https://roamresearch.com/#/app/bristol-clojure/page/KT5i16d-v)

### Templates and Examples

* https://github.com/dvingo/dv.fulcro-template - based on the fulcro3 template but differs in backend tech and will continue to diverge as features are added to this template.
* [Dvingo's pathom-client-wikipedia](https://github.com/dvingo/pathom-client-wikipedia) -  example client-only fulcro app hitting a rest api
* [PoC of a GUI and a teminal UI built with Fulcro](https://github.com/phronmophobic/membrane-fulcro) and [Membrane](https://github.com/phronmophobic/membrane)
