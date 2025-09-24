# Responsive Image Gallery

A clean, simple, and visually appealing image gallery created using only HTML5 and CSS3. This project features a responsive grid layout that adapts to different screen sizes and showcases interactive hover effects to engage users.

## ✨ Features

-   **Responsive Layout**: Built with CSS Flexbox to ensure the gallery looks great on desktops, tablets, and mobile devices.
-   **Interactive Hover Effects**:
    -   Images are grayscale by default and transition to full color on hover.
    -   Cards gently scale up and display a subtle drop shadow when hovered over.
    -   Image captions elegantly fade in and slide up from the bottom.
-   **Pure CSS**: No JavaScript is used, making the project lightweight and fast.
-   **Easy to Customize**: The structure is simple, and the CSS is well-commented, making it easy to modify styles, colors, and content.
-   **Google Fonts Integration**: Uses the "Poppins" font for clean and modern typography.

## 📸 Demo

When a user hovers over an image card, the following happens:
1.  The grayscale image smoothly transitions to full color.
2.  The card scales up slightly with a `transform`.
3.  A `drop-shadow` appears behind the card.
4.  The hidden caption fades in and moves into view.


*(Note: You can replace this with a real GIF of your project in action.)*

## 🛠️ Technologies Used

-   **HTML5**: For the structure and content of the gallery.
-   **CSS3**: For styling, layout (Flexbox), and animations (Transitions, Transforms, Filters).

## 🚀 How to Use

To get this project up and running on your local machine, follow these simple steps.

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    ```

2.  **Navigate to the project directory:**
    ```sh
    cd your-repo-name
    ```

3.  **Add your images:**
    -   Create a folder named `img` in the root of the project directory.
    -   Place all your desired images inside this new `img` folder.

4.  **Update the HTML:**
    -   Open the `index.html` file.
    -   Modify the `<figure>` blocks to match your images. For each image, update the `src` attribute of the `<img>` tag and the text content of the `<figcaption>` tag.

    ```html
    <figure class="card">
      <img src="./img/your-image-name.jpg" />
      <figcaption>Your Caption Here</figcaption>
    </figure>
    ```
    -   Add or remove `<figure class="card">...</figure>` blocks as needed.

5.  **View in browser:**
    -   Simply open the `index.html` file in your favorite web browser to see the gallery.

## 🎨 Customization

You can easily customize the gallery by editing the `styles.css` file.
-   **Colors**: Change the `background-color` on the `body` or the `color` of the `h1` heading.
-   **Fonts**: The project uses "Poppins" from Google Fonts. You can change this by updating the `@import` rule at the top of `styles.css` and changing the `font-family` property.
-   **Animations**: Adjust the `transition` duration in the `.card` and `.card:hover figcaption` rules to make the animations faster or slower.

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
