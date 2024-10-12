# 2.ShapePlotter
---

# SHAPEPlotter

## Project Description
The `SHAPEPlotter` project provides a simple console application for creating and saving various geometric shapes, including points, lines, triangles, rectangles, squares, circles, and polygons. The shapes are defined through user input and are written to an output file for visualization.

---

## Project Structure

- **Header Files:**
  - [Circle.h](SHAPEPlotter/HeaderFiles/Circle.h): Defines the `Circle` class.
  - [FileWriter.h](SHAPEPlotter/HeaderFiles/Filewriter.h): Implements file writing functionalities.
  - [Line.h](SHAPEPlotter/HeaderFiles/Line.h): Defines the `Line` class.
  - [Manager.h](SHAPEPlotter/HeaderFiles/Manager.h): Manages user input and shape creation.
  - [Point.h](SHAPEPlotter/HeaderFiles/Point.h): Defines the `Point` class.
  - [Polygon.h](SHAPEPlotter/HeaderFiles/Polygon.h): Defines the `Polygon` class.
  - [Rectangle.h](SHAPEPlotter/HeaderFiles/Rectangle.h): Defines the `Rectangle` class.
  - [Square.h](SHAPEPlotter/HeaderFiles/Square.h): Defines the `Square` class, derived from `Rectangle`.
  - [Triangle.h](SHAPEPlotter/HeaderFiles/Triangle.h): Defines the `Triangle` class.

- **Source Files:**
  - [Circle.cpp](SHAPEPlotter/SourceFile/Circle.cpp): Implements `Circle` class functionalities.
  - [Filewriter.cpp](SHAPEPlotter/SourceFile/Filewriter.cpp): Implements file writing functionalities.
  - [Line.cpp](SHAPEPlotter/SourceFile/Line.cpp): Implements `Line` class functionalities.
  - [Manager.cpp](SHAPEPlotter/SourceFile/Manager.cpp): Manages user input and shape operations.
  - [Point.cpp](SHAPEPlotter/SourceFile/Point.cpp): Implements `Point` class functionalities.
  - [Polygon.cpp](SHAPEPlotter/SourceFile/Polygon.cpp): Implements `Polygon` class functionalities.
  - [Rectangle.cpp](SHAPEPlotter/SourceFile/Rectangle.cpp): Implements `Rectangle` class functionalities.
  - [Square.cpp](SHAPEPlotter/SourceFile/Square.cpp): Implements `Square` class functionalities.
  - [Triangle.cpp](SHAPEPlotter/SourceFile/Triangle.cpp): Implements `Triangle` class functionalities.
  - [SHAPEPlotter.cpp](SHAPEPlotter/SourceFile/SHAPEPlotter.cpp): Main program execution.

---

## Feature Implementation

1. **Shape Creation**: Users can create different shapes by selecting from a menu and providing required parameters.
   - **Data Structure**: Utilizes classes to represent different geometric shapes, ensuring modularity and reusability in code.
   - **Graphics Representation**: Shapes are represented in a format compatible with visualization tools, enabling easy plotting and rendering.

2. **File Output**: Shapes are written to `output.dat`, which can be visualized using plotting tools.

---

## Visualizing Output

To visualize the output shapes, you can use gnuplot with the following command:
```bash
plot '.....\output.dat' w lp lt 3

```

### Output Snapshot:
- [Point Output](https://github.com/AbhishekSCCTech/2.ShapePlotter/blob/main/Output/1.Point.PNG)
- [Line Output](https://github.com/AbhishekSCCTech/2.ShapePlotter/blob/main/Output/2.Line.PNG)
- [Triangle Output](https://github.com/AbhishekSCCTech/2.ShapePlotter/blob/main/Output/3.Triangle.PNG)
- [Rectangle Output](https://github.com/AbhishekSCCTech/2.ShapePlotter/blob/main/Output/4.Rectangle.PNG)
- [Square Output](https://github.com/AbhishekSCCTech/2.ShapePlotter/blob/main/Output/5.Square.PNG)
- [Circle Output](https://github.com/AbhishekSCCTech/2.ShapePlotter/blob/main/Output/6.Circle.PNG)
- [Polygon Output](https://github.com/AbhishekSCCTech/2.ShapePlotter/blob/main/Output/7.Polygon.PNG)
- [Console Display Output](https://github.com/AbhishekSCCTech/2.ShapePlotter/blob/main/Output/console%20display.PNG)

---
