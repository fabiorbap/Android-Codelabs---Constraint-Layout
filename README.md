# Android Codelabs - Constraint Layout
Repository with the Constraint Layout Codelabs exercises

What I learned:

- There is a button that can automatically set the constraints for the views
- You can search and download a font to the project using Android Studio
- You can set default margins for all constraints in the editor
- The constraint bias is 50% by default, and it can be adjusted so that the view stays where it should be, according to the constraints.
- It is usually a good idea to have the width or height of the view as `match_constraints`, which means that it will be responsive according to the space available onscreen.
- It's possible to test the layout in devices with different resolutions, and also test how the layout works in landscape mode
- It's easy to extract a text or a dimension to a resource
- The concept of chains is used to associate views vertically or horizontally. The first element of the chain is called head of the chain, and it can be used to determine where the elements will be by using the constraint bias. There are some chain styles that can be set, like:
    - Spread: views spaced equally
    - Spread inside: views in the extremities are aligned to the parent, and the views between them are spaced equally
    - Packed: views don't have space between themselves, and the space the pack and the parent is equal
    - Weighed: each view will fill a space equivalent to its weight
