### Adding a basic ordered list of weekly food menu items to the HTML website

        Assumptions for a single page website:
        1. Hosted in GitHub Pages via a GitHub repository.
        2. Placeholders are added for the credentials only with the users

#### 1. Locating the webpage to edit

1. Login to GitHub with `<username>` and `<password>`.
2. Open the repository `<repo-name>` of your restaurant’s website.
3. Locate the **HTML** file (*`restaurantmenu.html` in the example screenshot below*), and click the **Edit Icon**<img src="https://raw.githubusercontent.com/Olena1925/Menu/master/Edit%20Icon.png" width="20" height="15"/> to open the GitHub editor.

<a href="https://raw.githubusercontent.com/Olena1925/Ordered-List/master/adding_menu.jpg" target="blank">
<img src="https://raw.githubusercontent.com/Olena1925/Ordered-List/master/adding_menu.jpg" width="290" height="160" align="middle" alt="Open in New Tab" style = "display: block; margin-left: auto; margin-right:auto;"/></a>

#### 2. Adding a basic ordered list of weekly menu

4. In the GitHub editor, add your weekly ordered list in the HTML format as specified in the sample below:

    ```html
    <html>
        <body>
            <h2>Weekly Food Menu</h2>
            <ol type = "1">
                <li>Monday: Asparagus with Porched Eggs</li>
                <li>Tuesday: Tiramisu with homemade Mascarpone</li>
                <li>Wednesday: Bramborové knedlíky s uzeným masem</li>
                <li>Thursday: Pork Ribs with Draught Beer</li>
                <li>Friday: Salade niçoise</li>
            </ol>  
        </body>
    </html>
    ```
5. Select the option **Commit directly to the `master` branch**.
6. Push the <span style="background-color: #00cc00"><span style="color: white;">Commit changes</span></span> button to save the weekly menu in the webpage.

> **Tip**: Visit [GitHub Pages](https://pages.github.com) for learning more about hosting the website.
