# Javascript Loop While and Do-while

## Flowchart Loop While
Membuat Flowchart untuk program Perulangan While yang menghasilkan pattern segitiga

```mermaid

   flowchart TD
   a@{ shape: circle, label: "Start" }
   b@{ shape: lean-r, label: " str = ' '" }
   c@{ shape: rect, label: " j = 1 " }
   d@{ shape: diamond, label: " j <= 4" }
   e@{ shape: rect, label: " str += ' * '" }
   g@{ shape: lean-r, label: " '{str}'" }
   f@{ shape: rect, label: " j++" }
   h@{ shape: dbl-circ, label: "Stop" }

    a --> b --> c --> d

    d --True--> e --> g --> f
    f --> d

    d --False--> h


```

## Flowchart Do-While

Membuat Flowchart untuk program Perulangan Do-While yang menghasilkan pattern segitiga

```mermaid

    flowchart TD

    a@{ shape: circle, label: "Start" }
    b@{ shape: lean-r, label: " str = ' '" }
    c@{ shape: rect, label: " j = 1" }
    d@{ shape: diamond, label: "j <= 5" }
    e@{ shape: rect, label: " str += ' * '" }
    g@{ shape: lean-r, label: " '{str}'" }
    f@{ shape: rect, label: " j++" }

    h@{ shape: dbl-circ, label: "Stop" }

    a --> b --> c --> e

    d --True--> e --> g --> f
    f --> d

    d --False--> h

```
