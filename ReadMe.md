# GUiFAD (Generic UI For Any Data Model)

## Abstract

Yet, this is a non-functional click dummy to illustrate my UI pattern which was designed to cope as frontend for managing master data.
One could search, create, edit, update, delete any kind of entity here.

The pattern avoids modal dialogs although it can handle nested relations (aka "1:N" or "composition"), junctions (aka "M:N"), lookups (aka "N:1").

It's "generic", because you don't need to design anything by hand, but the UI could be generated at runtime on base of any relational data model that
has a few attributes to mark relation roles like "principal", "lookup".

Although it's a generic UI with no manual optimization, it provides a maximum of usability, because it keeps the balance between information overkill
and necessary features.

## Future

This pattern is not purely theoretical. It has been fully implemented (non-generic) in an enterprise product that was used by thousands of users.
It is planned to create a functional generic .net component that can interpret data models (e.g. EF code first) and render a fully functional UI
without configuration or programming.
