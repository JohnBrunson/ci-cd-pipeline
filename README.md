# CI-CD Pipeline Demo

## Description
In interest of making development more professional, I've setup a CI-CD pipeline. Continuous Integreation/Continuous Development allows for new software to be put in front of customers regularly. However, the cost of doing that to the developer is that we need to sometimes ensure that the quality of the code is good and that we aren't simply making a lot of mistakes or worse, breaking production.

This sample method is effectively putting a lot of stop gaps in place so that the code is of quality and making sure that we get the benefits of automated testing.

If the tests pass, the item is pushed out to the development platform of choice (in this case, Render)

## Installation

Simply clone the repo and run ```npm i``` 

## Usage

The github actions are setup so that when develop is triggered, the component tests run. Likewise, for main, the tests run as a double check (it's probably not strictly necessary. For a production application, it might be advisable to include end to end tests here.) and if the tests pass again, then the code is pushed to render.

## Credits
N/A

## License
[MIT](https://choosealicense.com/licenses/mit/)