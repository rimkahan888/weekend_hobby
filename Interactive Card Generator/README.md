# Tailwind CSS Card Generator

![Tailwind CSS Card Generator Preview](https://via.placeholder.com/800x500?text=Tailwind+CSS+Card+Generator+Preview)

An interactive tool that generates customizable cards using Tailwind CSS, complete with a step-by-step tutorial on card creation.

## Features

- 🎨 **Live Customization**: Adjust card content and styling in real-time
- 📝 **Content Control**: Edit title, content, and button text
- 🖌️ **Style Options**: Choose from multiple colors, borders, and shadow effects
- 👀 **Instant Preview**: See changes as you make them
- 💻 **Code Output**: Get the generated HTML code for your custom card
- 📚 **Built-in Tutorial**: Learn how to create cards with Tailwind CSS


## How to Use

1. **Clone or Download** the repository
2. **Open** `index.html` in your browser
3. **Customize** your card using the controls:
   - Edit text content (title, body, button)
   - Select background color
   - Choose border style
   - Adjust shadow intensity
4. **Copy** the generated HTML code for use in your projects
5. **Learn** from the step-by-step tutorial at the bottom of the page

## Tutorial Overview

The built-in tutorial covers:

1. **Setting up your HTML file** with Tailwind CSS
2. **Creating the card container** with basic styling
3. **Adding card content** with proper spacing
4. **Styling interactive buttons** with hover effects
5. **Customization techniques** for unique designs

## Code Example

Here's a basic example of what the generator produces:

```html
<div class="bg-white border border-gray-200 shadow-md rounded-lg p-6 max-w-sm mx-auto">
    <h3 class="text-xl font-bold mb-2">Card Title</h3>
    <p class="text-gray-600 mb-4">This is some card content.</p>
    <button class="bg-blue-500 hover:bg-blue-600 text-white px-4 py-2 rounded transition-colors">
        Learn More
    </button>
</div>
