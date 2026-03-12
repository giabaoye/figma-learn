# figma-learn
Learning figma
## Definition
Frames: a core building block in Figma
- They act as **container** for other layers allowing you to organize them into cohesive designs
- We can use frames to create individual assets like icons or buttons. Or various segments of your design--like a navigation bar, screen, or layout for a website or mobile app design

## Constraints Fundamentals
Constraints allow us to determine how child layers respond when their parent frame is resized
By default, constraints are set to Top and Left, which means that the layer will stay in the same position relative to the top left corner of its parent frame when we resize the parent
further documentation: [Work with layers](https://help.figma.com/hc/en-us/articles/360039957734-Apply-constraints-to-define-how-layers-resize)

## Use smart selection to rearrange layers
When a selection of objects are spaced evenly apart on both the horizontal and vertical axes, you get access to smart selection
**Smart selection** lets us quickly rearrange and adjust spacing between two or more layers in a selection without having to go through the tedious task of adjusting it manually

## Sections, Frames
Sections: content, content, content, organizing our content\
Frames: container, container, container, hold our content and foundational piece for a lot of different things\
Groups

## Components Fundamentals
Components are reusable design elements. There are two aspects to a component:
- The **main component** that defines the properties of the design element
- And an **instance** that's a copy of the component, which we can add to our designs

## Flattening objects
- Flattening an object merge its layers into a single vector layer, simplifying the design, reducing the file size, and improving asset compatibility
- We can flatten a selection of vector layers to merge them into a complex vector shape. Or, flatten a text layer to customize aspects of a typeface of logos or wordmarks. Flattening a container layer, like frames or sections, will merge its child layers together and remove the container layer from the canvas
- Flattening is a **destructive** action. Once an object is flattened, its individual layers cannot be separated again.

## Prototyping fundamentals
Prototyping is a set of features, settings, and properties that define how parts of your designs behave when people interact with them
### Flows
Prototypes are made up of Flows. These flows describe the journeys people can take through a design, usually across multiple screens--like a sign up flow, or a checkout flow

### Interactions
Interactions are rules we set for how your prototype will respond to user inputs
They are made of a few smaller parts: a trigger, an action and an animation
Learn more: [https://help.figma.com/hc/en-us/articles/360040315773-Connect-your-prototype#01H8ET45XCPNKN86XD9Y5PMF5T](interactions)

#### Triggers
A trigger is what causes an interaction to begin
[https://help.figma.com/hc/en-us/articles/360040035834-Prototype-triggers](prototype triggers)
#### Action
An action is the result of a trigger
[https://help.figma.com/hc/en-us/articles/360040035874-Prototype-actions](prototype actions)
#### Animations
An animation defines how different properties, or objects, animate over time
[https://help.figma.com/hc/en-us/articles/360040522373-Prototype-animations](prototype animations)
#### Connections
Connections are used to string together frames and assets into a logical navigation flow for our prototype. We can identify connections by the blue arrows on the canvas, which we sometimes call "noodles"
[https://help.figma.com/hc/en-us/articles/360040314193-Guide-to-prototyping-in-Figma#h_01HHN4WWN3YDJ27498DVE6K3E1](prototype connections)
