# 3D Modern Periodic Table Using A-Frame

This project presents a 3D interactive visualization of the modern periodic table of elements using A-Frame, an open-source web framework for building virtual reality (VR) experiences with HTML.

- **Live** 🔗: [https://3dmpt.netlify.app](https://3dmpt.netlify.app)

![Website Preview](https://raw.githubusercontent.com/riteshgharat/3d-modern-periodic-table/main/SS.png)

## Features

- **3D Visualization**: Elements of the periodic table are represented as 3D boxes with their symbols and names.
- **Customizable**: Easily adjust the appearance and arrangement of elements using simple HTML attributes.
- **Interactivity**: Navigate through the 3D scene using mouse or touch controls.

## Technologies Used

- **A-Frame**: A web framework for building VR experiences. It allows the creation of 3D scenes using HTML.
- **HTML**: The basic structure and layout of the periodic table.
- **JavaScript**: Custom A-Frame components for rendering the elements and modifying the renderer.

## Code Overview

- **A-Frame Components**: The project defines two custom A-Frame components: `modify-renderer` and `element`. The `element` component is responsible for creating the 3D boxes that represent each element in the periodic table, along with their text labels.
- **Scene Setup**: The 3D scene is composed of a cylindrical ground, a sky background, and an entity representing the periodic table, all defined within the `<a-scene>` tag.

### Example

Below is a simple example of how an element is represented:

```html
<a-entity element="symbol: H; name: Hydrogen; color: #FFFFFF" position="-7 4 0"></a-entity>
```
