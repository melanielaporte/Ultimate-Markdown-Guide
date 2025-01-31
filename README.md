<h1 align="center">:wrench: Ultimate Markdown Guide :wrench:</h1>

Here is a go-to resource for mastering Markdown syntax and creating beautifully formatted documents. 
<p>Whether you're a beginner or a seasoned pro, this cheatsheet is designed to help you quickly reference and utilize Markdown effectively.</p>

---

## Table of Contents
- [Text Decoration](#text-decoration)
- [Headings](#headings)
- [Footnotes](#footnotes)
- [Lines](#lines)
- [Lists](#lists)
- [Links](#links)
- [Tables](#tables)
- [Graphs](#graphs)
- [Emojis](#emojis)
- [Tips and Tricks](#tips-and-tricks)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

Markdown is a lightweight markup language that allows you to create formatted text using a plain-text editor. It's widely used in documentation, websites, and collaborative platforms like GitHub.

Here’s what you’ll learn in this cheatsheet:
- Essential Markdown syntax.
- Advanced features like tables, code blocks, and footnotes.
- Tips to enhance your Markdown documents.

---

## Text Decoration

Here’s how to style your text:

- **Bold**: `**bold text**` → **bold text**  
- *Italic*: `*italic text*` → *italic text*  
- ~~Strikethrough~~: `~~strikethrough~~` → ~~strikethrough~~  
- Inline Code: `` `code` `` → `code`
- Math equation superscript: `$$E = mc^2$$` →  $$E = mc^2$$
- Math equation subscript: `H<sub>2</sub>O (Water)` → H<sub>2</sub>O (Water)
- Highlighted: `<mark>This text is highlighted.</mark> ` → <mark>This text is highlighted.</mark> 
- Small/tiny print: `This is <sub>small or fine </sub>print text.
 ` → This is <sub>small or fine </sub>print text. 
- Keyboard shortbuts: `` Press `Ctrl` + `C` to copy `` → Press `Ctrl` + `C` to copy

---

## Headings 
# h1 ` # h1 ` 
## h2 ` ## h2 `  
### h3 ` ### h3 ` 
#### h4 ` #### h4 ` 
##### h5 ` ##### h5 ` 
###### h6 ` ###### h6 ` 


---

## Footnotes 

![Screenshot Capture - 2025-01-17 - 05-24-49](https://github.com/user-attachments/assets/63d13bb5-ae6d-43cc-a4cd-2444d06c219c)

Here's a statement with a footnote.[^1] 

[^1]: This is the footnote text.

(the footnote reference is at this page bottom)
![Screenshot Capture - 2025-01-17 - 05-20-53](https://github.com/user-attachments/assets/b1855ca5-6297-4438-8d31-520ec50a0dc7)


---


## Lines

- Horizontal

--- 
***
___

- Indented <br>
&nbsp; &nbsp; ---


---

##### LISTS

- Fruit - Apples
  
  - Red
  - Green

##### TASKS - (Clickable in an Issue)
  
- [ ] Example 1
- [x] Example 2 completed
- [ ] Example 3
---

## Links

![Screenshot Capture - 2025-01-11 - 09-54-18](https://github.com/user-attachments/assets/a67a36b9-9dbf-4070-8626-3dd2dfb78367)
[Visit Mozilla](https://www.mozilla.org)

---

## Images 
![Screenshot Capture - 2025-01-11 - 09-49-45](https://github.com/user-attachments/assets/54bf0edb-86b8-4590-ac9f-2c21be7690c4)
![ball](https://github.com/user-attachments/assets/1c0d421c-ffee-4426-a258-46435fd90d88)

---


# Tables
### Table Alignment
| Left-Aligned | Center-Aligned | Right-Aligned |
| :----------- | :------------: | ------------: |
| Item 1       |     Item 2     |        Item 3 |

- :-- means the column is left aligned.
- --: means the column is right aligned.
- :-: means the column is center aligned.

### 2 Column Table
| Month    | Savings |
| -------- | ------- |
| January  | $250    |
| February | $80     |
| March    | $420    |

### 3 Column Table
| Item              | In Stock | Price |
| :---------------- | :------: | ----: |
| Python Hat        |   True   | 23.99 |
| SQL Hat           |   True   | 23.99 |
| Codecademy Tee    |  False   | 19.99 |
| Codecademy Hoodie |  False   | 42.99 |

### 3 Column Table with Images
|Content    |Example1    |Example2    |
| --- | --- | --- |
| <img width="200" atl="ball1" src="https://github.com/user-attachments/assets/569decce-86c8-40e4-a145-d6182cb8ca74"> | <img width="200" atl="ball2" src="https://github.com/user-attachments/assets/569decce-86c8-40e4-a145-d6182cb8ca74"> | <img width="200" atl="ball3" src="https://github.com/user-attachments/assets/569decce-86c8-40e4-a145-d6182cb8ca74">|
| <img width="200" atl="ball4" src="https://github.com/user-attachments/assets/569decce-86c8-40e4-a145-d6182cb8ca74"> | <img width="200" atl="ball5" src="https://github.com/user-attachments/assets/569decce-86c8-40e4-a145-d6182cb8ca74"> | <img width="200" atl="ball6" src="https://github.com/user-attachments/assets/569decce-86c8-40e4-a145-d6182cb8ca74"> |
| <img width="200" atl="ball7" src="https://github.com/user-attachments/assets/569decce-86c8-40e4-a145-d6182cb8ca74"> | <img width="200" atl="ball8" src="https://github.com/user-attachments/assets/569decce-86c8-40e4-a145-d6182cb8ca74"> | <img width="200" atl="ball9" src="https://github.com/user-attachments/assets/569decce-86c8-40e4-a145-d6182cb8ca74"> |  

---

## Graphs
The best way to add graphs in Markdown is with [Mermaid](https://mermaid.js.org/). It is a JavaScript-based diagramming and charting tool that integrates seamlessly with Markdown. It allows users to create visually appealing diagrams, such as flowcharts, sequence diagrams, Gantt charts, and more, directly within Markdown documents using a simple and intuitive syntax. By embedding Mermaid code blocks in Markdown, you can dynamically generate diagrams that are easy to maintain and share, making it a popular choice for documentation and technical writing.

<p>You can make many types of graphs, from diagrams to flow chart.</p>

#### Pie Chart
![Screenshot Capture - 2025-01-15 - 07-29-54](https://github.com/user-attachments/assets/0d65d295-1f12-47d6-8184-4660fb3c2c44)

```mermaid
%%{init: {"pie": {"textPosition": 0.5}, "themeVariables": {"pieOuterStrokeWidth": "5px"}} }%%
pie showData
    title Key elements in Product X
    "Calcium" : 42.96
    "Potassium" : 50.05
    "Magnesium" : 10.01
    "Iron" :  5
```
#### Bar Chart
![Screenshot Capture - 2025-01-15 - 07-30-28](https://github.com/user-attachments/assets/3eb42b08-c10c-408b-b8b2-9f6d168df0aa)

```mermaid
    xychart-beta
    title "Sales Revenue"
    x-axis [jan, feb, mar, apr, may, jun, jul, aug, sep, oct, nov, dec]
    y-axis "Revenue (in $)" 4000 --> 11000
    bar [5000, 6000, 7500, 8200, 9500, 10500, 11000, 10200, 9200, 8500, 7000, 6000]
    line [5000, 6000, 7500, 8200, 9500, 10500, 11000, 10200, 9200, 8500, 7000, 6000]
 ```   
#### Diagram
![Screenshot Capture - 2025-01-15 - 07-31-20](https://github.com/user-attachments/assets/5e48d5c1-40eb-4fe4-a525-2777bfd55177)

```mermaid
  graph TD;
      A-->B;
      A-->C;
      B-->D;
      C-->D;
```
#### Diagram
![Screenshot Capture - 2025-01-15 - 07-31-35](https://github.com/user-attachments/assets/a7aecb65-39f6-463e-a873-7ae759bad50f)

```mermaid
sequenceDiagram
    participant dotcom
    participant iframe
    participant viewscreen
    dotcom->>iframe: loads html w/ iframe url
    iframe->>viewscreen: request template
    viewscreen->>iframe: html & javascript
    iframe->>dotcom: iframe ready
    dotcom->>iframe: set mermaid data on iframe
    iframe->>iframe: render mermaid
```
#### Mindmap
![Screenshot Capture - 2025-01-15 - 07-31-51](https://github.com/user-attachments/assets/55d631e4-9484-458a-9168-5742b7213e51)

```mermaid
 mindmap
  root((mindmap))
    Origins
      Long history
      ::icon(fa fa-book)
      Popularisation
        British popular psychology author Tony Buzan
    Research
      On effectivness<br/>and features
      On Automatic creation
        Uses
            Creative techniques
            Strategic planning
            Argument mapping
    Tools
      Pen and paper
      Mermaid
```
#### User Journey Chart
![Screenshot Capture - 2025-01-15 - 07-32-06](https://github.com/user-attachments/assets/b0af5f92-3446-47e3-84ef-f148bc6022b1)

```mermaid
 journey
    title My working day
    section Go to work
      Make tea: 5: Me
      Go upstairs: 3: Me
      Do work: 1: Me, Cat
    section Go home
      Go downstairs: 5: Me
      Sit down: 3: Me
```
#### Block Chart
![Screenshot Capture - 2025-01-15 - 07-32-18](https://github.com/user-attachments/assets/a64e42be-dad3-4d46-8bbf-f3a030b21fc7)

```mermaid
 block-beta
    columns 3
    doc>"Document"]:3
    space down1<[" "]>(down) space

  block:e:3
          l["left"]
          m("A wide one in the middle")
          r["right"]
  end
    space down2<[" "]>(down) space
    db[("DB")]:3
    space:3
    D space C
    db --> D
    C --> db
    D --> C
    style m fill:#d6d,stroke:#333,stroke-width:4px
    
```
#### Git Hierarchy Graph
![Screenshot Capture - 2025-01-15 - 07-32-53](https://github.com/user-attachments/assets/c433d090-0707-44ae-bd5a-cf0b6519fea3)

```mermaid
 gitGraph
    commit
    commit
    branch develop
    checkout develop
    commit
    commit
    checkout main
    merge develop
    commit
    commit
```
#### Packet Graph
![Screenshot Capture - 2025-01-15 - 07-33-06](https://github.com/user-attachments/assets/728827bc-4804-4aa9-995e-ff5fafb7b4c7)

```mermaid
 ---
title: "TCP Packet"
---
packet-beta
  0-15: "Source Port"
  16-31: "Destination Port"
  32-63: "Sequence Number"
  64-95: "Acknowledgment Number"
  96-99: "Data Offset"
  100-105: "Reserved"
  106: "URG"
  107: "ACK"
  108: "PSH"
  109: "RST"
  110: "SYN"
  111: "FIN"
  112-127: "Window"
  128-143: "Checksum"
  144-159: "Urgent Pointer"
  160-191: "(Options and Padding)"
  192-255: "Data (variable length)"
```
#### Class Diagram
![Screenshot Capture - 2025-01-15 - 07-33-19](https://github.com/user-attachments/assets/e4d41432-b78c-46be-864c-3753da870f98)

```mermaid
 classDiagram
    Animal <|-- Duck
    Animal <|-- Fish
    Animal <|-- Zebra
    Animal : +int age
    Animal : +String gender
    Animal: +isMammal()
    Animal: +mate()
    class Duck{
      +String beakColor
      +swim()
      +quack()
    }
    class Fish{
      -int sizeInFeet
      -canEat()
    }
    class Zebra{
      +bool is_wild
      +run()
    }
```
#### Quadrant Chart
![Screenshot Capture - 2025-01-15 - 07-33-33](https://github.com/user-attachments/assets/076ffed5-457c-4616-b164-c841edf85444)

```mermaid
quadrantChart
    title Reach and engagement of campaigns
    x-axis Low Reach --> High Reach
    y-axis Low Engagement --> High Engagement
    quadrant-1 We should expand
    quadrant-2 Need to promote
    quadrant-3 Re-evaluate
    quadrant-4 May be improved
    Campaign A: [0.3, 0.6]
    Campaign B: [0.45, 0.23]
    Campaign C: [0.57, 0.69]
    Campaign D: [0.78, 0.34]
    Campaign E: [0.40, 0.34]
    Campaign F: [0.35, 0.78]  
```
#### ER Chart
![Screenshot Capture - 2025-01-15 - 07-33-43](https://github.com/user-attachments/assets/63235143-1f72-4b72-a190-cbef3da6ae34)

```mermaid
 erDiagram
    CUSTOMER }|..|{ DELIVERY-ADDRESS : has
    CUSTOMER ||--o{ ORDER : places
    CUSTOMER ||--o{ INVOICE : "liable for"
    DELIVERY-ADDRESS ||--o{ ORDER : receives
    INVOICE ||--|{ ORDER : covers
    ORDER ||--|{ ORDER-ITEM : includes
    PRODUCT-CATEGORY ||--|{ PRODUCT : contains
    PRODUCT ||--o{ ORDER-ITEM : "ordered in"
```

---


## Emojis
Make your text fun and engaging with emojis:

- Smile: `:smile: ` → :smile:
- Rocket: `:rocket: ` → :rocket:
- Celebration: `:tada: ` → :tada:

| **Category**      | **Emoji**           | **Description**        |
|--------------------|---------------------|------------------------|
| **Science**        | 🔬 `:microscope:`  | Microscope            |
|                    | 🧬 `:dna:`         | DNA                   |
|                    | ⚛️ `:atom_symbol:` | Atom Symbol           |
|                    | 🌡️ `:thermometer:` | Thermometer           |
|                    | 💊 `:pill:`        | Pill                  |
|                    | 🧪 `:test_tube:`   | Test Tube             |
|                    | 🧫 `:petri_dish:`  | Petri Dish            |
|                    | 🧹 `:broom:`       | Broom (Lab Cleanliness)|
|                    | 🔭 `:telescope:`   | Telescope             |
|                    | 🌌 `:milky_way:`   | Milky Way             |
|                    | 🌕 `:full_moon:`   | Full Moon             |
|                    | 🪐 `:ringed_planet:` | Ringed Planet       |
|                    | 🛰️ `:satellite:`   | Satellite             |
|                    | 🚀 `:rocket:`      | Rocket                |
|                    | 🔋 `:battery:`     | Battery               |
| **Engineering**    | ⚙️ `:gear:`         | Gear                  |
|                    | 🛠️ `:hammer_and_wrench:` | Hammer and Wrench|
|                    | 🔧 `:wrench:`      | Wrench                |
|                    | 🧰 `:toolbox:`     | Toolbox               |
|                    | 🏗️ `:building_construction:` | Building Construction |
|                    | 🖥️ `:desktop_computer:` | Desktop Computer  |
|                    | 🖲️ `:trackball:`   | Trackball             |
|                    | 💻 `:laptop:`      | Laptop                |
|                    | 🔌 `:electric_plug:` | Electric Plug       |
|                    | 📡 `:satellite_antenna:` | Satellite Antenna |
|                    | 🕹️ `:joystick:`    | Joystick              |
|                    | 🔩 `:nut_and_bolt:` | Nut and Bolt         |
| **Technology**     | 🤖 `:robot:`       | Robot                 |
|                    | 📱 `:iphone:`      | Smartphone            |
|                    | 🖱️ `:computer_mouse:` | Computer Mouse    |
|                    | 🧑‍💻 `:technologist:` | Technologist        |
|                    | 🔒 `:lock:`        | Lock (Cybersecurity)  |
|                    | 📡 `:satellite_antenna:` | Satellite Antenna |
|                    | 📊 `:bar_chart:`   | Bar Chart (Data Science) |
|                    | 🌐 `:globe_with_meridians:` | Globe with Meridians (Internet and Networking) |

## Tips and Tricks
##### Embedded HTML
Add collapsible sections or advanced styles with HTML:

![Screenshot Capture - 2025-01-11 - 09-03-24](https://github.com/user-attachments/assets/eac0e11a-152c-4c34-a439-da2c2efbfe0f)

<details>
  <summary>Click to expand</summary>
  Hidden content here.
</details>

##### Blockquotes Highlight code for various programming languages

- BLockquote: `> Normal Blockquote ` →
> Normal Blockquote
- BLockquote: `> **Bold Blockquote** ` →
> **Bold Blockquote**
- BLockquote: `> _Italic Blockquote_  ` →
> _Italic Blockquote_

##### Code blocks - highlight code for various programming languages
![Screenshot Capture - 2025-01-11 - 08-43-12](https://github.com/user-attachments/assets/8798e75e-d880-478b-8911-f2294e3c80b6)

```python
def hello_world():
    print("Hello, world!")
```
##### Hidden Comment

` [This is a hidden comment.]: #  `

##### DEFINITIONS

<dl>
  <dt><strong>Lower cost</strong></dt>
  <dd>The new version of this product costs significantly less than the previous one!</dd>
  <dt><strong>Easier to use</strong></dt>
  <dd>We've changed the product so that it's much easier to use!</dd>
  <dt><strong>Safe for kids</strong></dt>
  <dd>You can leave your kids alone in a room with this product and they
      won't get hurt (not a guarantee).</dd>
</dl>

---


## Contributing
Contributions are welcome! If you'd like to add more tips or improve the content, please feel free to open an issue or submit a pull request. Let's make this cheatsheet the best resource for Markdown enthusiasts!

---



## License
This project is licensed under the MIT License. See the LICENSE file for more details.


---


## Contact
Created by [Melanie Laporte](https://github.com/melanielaporte). If you have questions or suggestions, feel free to reach out or open an issue on GitHub.










