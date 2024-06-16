```mermaid
---
title: stratagus Class Diagram
---
classDiagram
  class CColor{
    +unsigned char R
	  +unsigned char G
	  +unsigned char B
	  +unsigned char A
    +void Parse(*l, index)
    +operator SDL_Color() const
    +operator IntColor() const
  }
```
