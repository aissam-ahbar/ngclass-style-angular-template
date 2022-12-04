# ngClass to add or remove class on CSS element

```
# app.component.css
.firstClass {
  color: white;
}

.secondClass {
  background-color: #1976d2;
}
```

```
# app.component.html
<div [ngClass]="'firstClass secondClass'">element1</div>

<div [ngClass]="['firstClass', 'secondClass']">element2</div>

<div [ngClass]="{ firstClass: true, secondClass: true }">element3</div>

<div [ngClass]="{ 'firstClass secondClass': true }">element5</div>
```
