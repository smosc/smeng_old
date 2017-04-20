# SMEng Frontend Libs

Documentation on SMEng, primarily its libs - basic stats, potential alternatives and why they weren't used.

- RESTful + AMD modal
- Built for function chaining
- In-browser crypto on sensitive data

- - -

- [LoDash](https://github.com/lodash/lodash/) (_25.1 kb_ @ [cdnjs](https://cdnjs.cloudflare.com/ajax/libs/lodash.js/4.17.4/lodash.min.js)) - Object manipulation
     > Alternative to [UnderscoreJS](https://github.com/jashkenas/underscore) -- I chose performance superiority over ease of use 

- [SJCL](https://github.com/bitwiseshiftleft/sjcl) (_25.3 kb_ @ [cdnjs](https://cdnjs.cloudflare.com/ajax/libs/sjcl/1.0.6/sjcl.min.js)) - Stanford Javascript Crypto Library

- [qoopido.demand](https://github.com/dlueth/qoopido.demand) (_18.9 kb_) - File loader using promises + localstorage cache
     > Alternative to [PromiseJS](https://www.promisejs.org/)/[BasketJS](https://addyosmani.com/basket.js/) - use qoopido due to being a nice mix of both alternatives
     
- [BlissfulJS](https://github.com/leaverou/bliss/) (_10.4 kb_ @ [cdnjs](https://cdnjs.cloudflare.com/ajax/libs/blissfuljs/1.0.4/bliss.min.js)) - Nicer JS; DOM manipulation & chaining jQuery inspired, without the overheads!
     > Alternatives: jQuery (too slow), [SprintJS](https://github.com/bendc/sprint) (Requires performance tests), [BitsyCode](https://www.bitsycode.com/) While very small (_7.1 kb_), it doesn't offer XHR methods like Blissful, [Umbrella](https://github.com/franciscop/umbrella) - jQuery like performance - which aint that good.

- [Template Resource](http://foundation.zurb.com/building-blocks/) - Material themed

> ## Rejected:
> - [KnockoutJS](http://knockoutjs.com/index.html) (_59 kb_) // [VueJS](https://github.com/vuejs/vue) (_74.9 kb_) -- Too large, and don't contribute enough at the moment.

- - -

| Lib           | Size          |
| ------------- |:-------------:|
| LoDash| 25.1 kb|
| SJCL| 25.3 kb |
| qoopido| 18.9 kb       |
| Bliss| 10.4 kb       |
| **Σ unoptimised**:| **79.7 kb**       |


- OS
