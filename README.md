<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/Prasenjit-3433/Drag-and-Drop">
    <img src="images/kanban.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Kanban Board</h3>

  <p align="center">
    A web-based, Kanban-style, project management tool feat. Drag and Drop API, localStorage 😎
    <br />
    <a href="https://github.com/Prasenjit-3433/Drag-and-Drop"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://kanbanboardjs.netlify.app/">View Demo</a>
    ·
    <a href="https://github.com/Prasenjit-3433/Drag-and-Drop/issues">Report Bug</a>
    ·
    <a href="https://github.com/Prasenjit-3433/Drag-and-Drop/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#-about-the-project">About The Project</a>
      <ul>
        <li><a href="#-built-with">Tech Stack</a></li>
      </ul>
    </li>
    <li>
      <a href="#-getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#%EF%B8%8F-implementation">Implementation</a></li>
    <li><a href="#-features">Features</a></li>
    <li><a href="#-contributing">Contributing</a></li>
    <li><a href="#-license">License</a></li>
    <li><a href="#-contact">Contact</a></li>
    <li><a href="#%EF%B8%8F-references">References</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## 🙋 About The Project

<!--  ![Screenshot](images/demo.gif) -->
<p align="center">
  <img src="images/demo.gif" alt="animated" />
</p>




"Kanban" is the Japanese word for "visual signal". If you work in services or technology, your work is often times invisible and intangible. A kanban board is an agile project management tool designed to help visualize work, limit work-in-progress, and maximize efficiency (or flow). It can help both `agile` and `DevOps` teams establish order in their daily work. Kanban boards use cards, columns, and continuous improvement to help technology and service teams commit to the right amount of work, and get it done!

Kanban has come a long way from its origins in lean manufacturing thanks to a small but mighty group of kanban enthusiasts. David Anderson’s work defining the kanban method helped bring kanban into the software and services space, and Personal Kanban, by Jim Benson and Tonianne DeMaria, helped expand the applications of kanban to places you wouldn’t believe. 🔥

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### 🛠 Built With

* ![HTML](https://img.shields.io/badge/HTML5-f06529?style=for-the-badge&logo=html5&logoColor=white)
* ![CSS](https://img.shields.io/badge/CSS3-2965f1?style=for-the-badge&logo=CSS3&logoColor=white)
* ![JavaScript](https://img.shields.io/badge/JavaScript-F0DB4F?style=for-the-badge&logo=JavaScript&logoColor=323330)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## 🚀 Getting Started

This is an example of how you may start on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* Live Server Extension
  ![Live-Server](images/liveserver.png)

### Installation

1. First of all install `Live Server` extension by `Ritwick Dey`.
2. Once the extension was installed, then `right-click` on `index.html` and select `Open with Live Server`.
3. It'll open a new tab in browser & start serving the Kanban Board. Enjoy!.


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## 🏗️ Implementation

* First of all, we need to gather all `functional requirements` of the Kanban Board. kanban boards can be broken down into five components: `Visual signals`, `columns`, `work-in-progress` limits, a `commitment point`, and a `delivery point`.

<details>
  <summary>More About Each Component</summary>
  <ol>
    <li>
      <p>Visual Signals — One of the first things you’ll notice about a kanban board are the visual cards (stickies, tickets, or otherwise). Kanban teams write all of their projects and work items onto cards, usually one per card. For agile teams, each card could encapsulate one user story. Once on the board, these visual signals help teammates and stakeholders quickly understand what the team is working on.</p>
    </li>
    <li>
      <p>Columns — Another hallmark of the kanban board are the columns. Each column represents a specific activity that together compose a “workflow”. Cards flow through the workflow until completion. Workflows can be as simple as “Backlog,” “In Progress,” “Complete,” or "On Hold".</p>
    </li>
    <li>
      <p>Work In Progress (WIP) Limits — WIP limits are the maximum number of cards that can be in one column at any given time. A column with a WIP limit of three cannot have more than three cards in it. When the column is “maxed-out” the team needs to swarm on those cards and move them forward before new cards can move into that stage of the workflow. These WIP limits are critical for exposing bottlenecks in the workflow and maximizing flow. WIP limits give you an early warning sign that you committed to too much work.</p>
    </li>
    <li>
      <p>Commitment point — Kanban teams often have a backlog for their board. This is where customers and teammates put ideas for projects that the team can pick up when they are ready. The commitment point is the moment when an idea is picked up by the team and work starts on the projec</p>
    </li>
    <li>
      <p>Delivery point — The delivery point is the end of a kanban team’s workflow. For most teams, the delivery point is when the product or service is in the hands of the customer. The team’s goal is to take cards from the commitment point to the delivery point as fast as possible. The elapsed time between the two is the called Lead Time. Kanban teams are continuously improving to decrease their lead time as much as possible.</p>
    </li>
  </ol>
</details>


<div align="center">
<img src="images/Elements_of_a_kanban_board.png" alt="Kanban Board" width="500" height="398">
</div> 



* Then break the whole board into small `Ui Components` & start building indivisual components.
<details>
<summary>Ui Components:</summary>
<ol>
<li>
    <details>
      <summary>Columns, Custom Scrollbar</summary>
      <ul>
        <li>an unordered list is going to hold these 4 columns & each column is going to contain another unordered list which'll hold all the task items.</li>
        <li>In each column, there'll be a header at top that indicates the type of the column, followed by task items and then at last, two buttons - add-item, save-item and a textbar which'll be hidden by default.</li>
        <li>Each task item can have a maximum height of 52% of viewport height, so that user can always sees the bottom of the column. </li>
        <li>If a column contains any task item with very long text, then in that case, a custom-designed scollbar will appear at side to scroll through the task items and at same item user can see whole column.</li>
        <div align="center"><img src="images/image2.png" alt="Kanban Columns" align="center" width="450" height="300"></div>
      </ul>
    </details>
  </li>
  </li>
  <li>
    <details>
      <summary>Connection between DOM & localStorage</summary>
      <ul>
        <li>First of all, we set 4 global arrays that'll hold all the contents for each 4 columns.</li>
        <li>On load of the page, it'll try to fetch data from localStorage if there's any and populate them into those arrays accordingly. Otherwise set some default contents for those 4 arrays.</li>
        <li>There's another global var to keep track if there's any changes made on those global 4 arrays.</li>
        <li>Then a function to update DOM. It'll create element for each item in those 4 arrays and insert them into their proper columns accordingly.</li>
      </ul>
    </details>
    </li>
  <li>
    <details>
      <summary>Drag-&-Drop Feature</summary>
      <ul>
        <li>First of all: To make an element draggable, set the `draggable` attribute to true</li>
        <li>Then, specify what should happen when the element is dragged. The `ondragstart` attribute calls a function, drag(event), that specifies what data to be dragged. The element is saved into a global var to keep track which element is being dragged and making it global as we need it in drop function as well later on.</li>
        <li>The ondragover event specifies where the dragged data can be dropped. By default, data/elements cannot be dropped in other elements. To allow a drop, we must prevent the default handling of the element. This is done by calling the event.preventDefault() method for the ondragover event.</li>
        <li>Do the Drop - ondrop: When the dragged data is dropped, a drop event occurs. Call preventDefault() to prevent the browser default handling of the data (default is open as link on drop).</li>
        <li>Add these methods on the element by `ondragover`, `ondrop` attributes.</li>
        <li>It'll be nice to have some visual reference to show that the column is ready to accept the incoming item. So the parent column and drop-target column take the colour of their head as their content's background color.</li>
        <li>On the fire of `dragenter` event, the parent column and drop-target column changes color & update their content.</li>
        <li>Finally, each time when an item moved to another column, all the global arrays that contains column data are rebuilt and updated localStrorage.</li>
      </ul>
    </details>
  </li>
  <li>
  <details>
      <summary>Add, Update, Delete an Item</summary>
    <ul>
        <li>On the click on `Add Item` button, an inputBox will appear and `add Item` button get vanished by `Save Item` button.</li>
        <li>Once an user entered his message and press `Save Item`, the message is pushed into localArrays, transferred into localStorage and DOM get updated!.</li>
        <li>At the time of creating item in the column, we also added contentEditable = true. So that later on, when user click on an item, he is able to edit/delete it.</li>
        <li>Now when an user click into an item, modified it and then leves the element, then `focusout` event get fired. The focusout event fires when an element is about to lose focus. On the fire of this event, the item is checked for if it does has text or not. If not, then remove it from the corresponding localArray & update the DOM. If it has text, then the current string in the corresponding localArray overwritten by new one & update the DOM.</li>
        <li>But in the above process, drag-drop functionlity get broken Because when an user click on an item, it's opening to be edited, meaning that the item's text content is in flux. As a result, when user drag it, because the text content is in flux and not saved, it does't have ability to copy it over to another column because it doesn't know what's its own value is.</li>
        <li>In order to fix this, we need to make sure that an item can be updated only if it is not being dragged. So we create a global variable to keep track whether an item is being dragged or not. At start of drag function, we set it to `true` and at the end of drop function set it back to false.</li>
      </ul>
    </details>
  </li>
</ol>
</details>

_For more information, visit necessary reference [Link](#%EF%B8%8F-references)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- Features -->
## 💎 Features

- [ ] **Flexibility**: Digital Kanban boards allow teams that do not share a physical office space to use kanban boards remotely and asynchronously. The setup involves just a few clicks to create digital lists, which represent the stages of your kanban process, on a board view that your whole team can access and manage.
- [ ] **Drag and Drop**: Once can move a task from one stage to another stage by just dragging and dropping the card.
- [ ] **Local Storage**: The setup uses browser's Local Storage to store the digital for faster data fetching. Even if the browser or tab get closed, all the data remain safe!. So that on the next page load, the board gets back to its previous state.

See the [open issues](https://github.com/Prasenjit-3433/Drag-and-Drop/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## 🤝 Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## 📜 License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## 📮 Contact

Prasenjit Sutradhar - [@twitter_handle](https://twitter.com/twitter_handle) - prasenjitsutradhar3433@gmail.com

Project Link: [https://github.com/Prasenjit-3433/Drag-and-Drop](https://github.com/Prasenjit-3433/Drag-and-Drop)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- references -->
## ✌️ References

* [CSS-Tricks: Custom Scrollbar](https://css-tricks.com/the-current-state-of-styling-scrollbars-in-css/)
* [w3schools - HTML Drag and Drop API](https://www.w3schools.com/html/html5_draganddrop.asp)
* [w3schools - HTML ondragenter Attribute](https://www.w3schools.com/tags/att_ondragenter.asp)
* [MDN - Making content editable](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Editable_content)
* [MDN - focusout event](https://developer.mozilla.org/en-US/docs/Web/API/Element/focusout_event)


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/Prasenjit-3433/Drag-and-Drop.svg?style=for-the-badge
[contributors-url]: https://github.com/Prasenjit-3433/Drag-and-Drop/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Prasenjit-3433/Drag-and-Drop.svg?style=for-the-badge
[forks-url]: https://github.com/Prasenjit-3433/Drag-and-Drop/network/members
[stars-shield]: https://img.shields.io/github/stars/Prasenjit-3433/Drag-and-Drop.svg?style=for-the-badge
[stars-url]: https://github.com/Prasenjit-3433/Drag-and-Drop/stargazers
[issues-shield]: https://img.shields.io/github/issues/Prasenjit-3433/Drag-and-Drop.svg?style=for-the-badge
[issues-url]: https://github.com/Prasenjit-3433/Drag-and-Drop/issues
[license-shield]: https://img.shields.io/github/license/Prasenjit-3433/Drag-and-Drop.svg?style=for-the-badge
[license-url]: https://github.com/Prasenjit-3433/Drag-and-Drop/blob/main/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://in.linkedin.com/
[product-screenshot]: images/screenshot.png
[HTML5]: https://img.shields.io/badge/HTML5-f06529?style=for-the-badge&logo=html5&logoColor=white
[HTML-url]: https://developer.mozilla.org/en-US/docs/Glossary/HTML5
[Css]: https://img.shields.io/badge/CSS3-2965f1?style=for-the-badge&logo=CSS3&logoColor=white
[Css-url]: https://developer.mozilla.org/en-US/docs/Web/CSS
[Js]: https://img.shields.io/badge/JavaScript-F0DB4F?style=for-the-badge&logo=JavaScript&logoColor=323330
[Js-url]: https://www.javascript.com/
