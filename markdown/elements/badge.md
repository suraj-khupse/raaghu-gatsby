---
slug: "/badge"
date: "2019-05-04"
title: "Elements > Badge"
---

<!-- CSS only -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
<link rel="stylesheet" href="../../../../../../../raaghu/src/assets/css/style-elements.css">
<link rel="stylesheet" href="../../../../../../../raaghu/src/assets/css/main.css">

#### Badge

<p class="checkbox-def">Use the Badge Component Symbol to draw attention to another interface element or to display a notification.</p>

<!-- Basic Example -->
<section class="py-4">
    <h6>Text Badge</h6>
    <div class="py-3">
      <div class="cust-tabs">
        <ul class="nav nav-tabs" id="myTab" role="tablist">
          <li class="nav-item" role="presentation">
            <button class="nav-link active" id="PreviewBasic-tab" data-bs-toggle="tab" data-bs-target="#PreviewBasic" type="button" role="tab" aria-controls="PreviewBasic" aria-selected="true">Preview </button>
          </li>
          <li class="nav-item" role="presentation">
            <button class="nav-link" id="AngularBasic-tab" data-bs-toggle="tab" data-bs-target="#AngularBasic" type="button" role="tab" aria-controls="AngularBasic" aria-selected="false"><i class="bi bi-code-slash" style="font-size:1.0rem"></i>Angular</button>
          </li>
          <li class="nav-item" role="presentation">
            <button class="nav-link" id="ReactBasic-tab" data-bs-toggle="tab" data-bs-target="#ReactBasic" type="button" role="tab" aria-controls="ReactBasic" aria-selected="false"><i class="bi bi-code-slash" style="font-size:1.0rem"></i>React</button>
          </li>
        </ul>
      </div>
      <div class="tab-content card border" id="myTabContent">
        <div class="tab-pane fade show active" id="PreviewBasic" role="tabpanel" aria-labelledby="PreviewBasic-tab">
          <div class="contents  p-5">
            <div class="row">
              <div class="col-12">
        <img src="/images/badge-basic.png" class="img-fluid">
          </div>
            </div>
          </div>
        </div>
        <div class="tab-pane fade show" id="AngularBasic" role="tabpanel" aria-labelledby="AngularBasic-tab">
          <div class="contents bg-code ">
<div class="row text-white m-0 p-4">

```html
<rds-badge
  size="medium"
  label="badge"
  badgeType="rectangle"
  colorVariant="danger"
></rds-badge>
```

</div>
          </div>
        </div>
<!-- React Start -->
        <div class="tab-pane fade show" id="ReactBasic" role="tabpanel" aria-labelledby="ReactBasic-tab">
          <div class="contents bg-code ">
<div class="row text-white m-0 p-4">

```html
<RdsBadge
  badgeType="rectangle"
  colorVariant="danger"
  label="Badge"
  size="medium"
/>
```

</div>
          </div>
        </div>
<!-- React end -->
      </div>
    </div>
  </section>
<section class="py-4">
    <h6>Button</h6>
    <div class="py-3">
      <div class="cust-tabs">
        <ul class="nav nav-tabs" id="myTab" role="tablist">
          <li class="nav-item" role="presentation">
            <button class="nav-link active" id="PreviewButton-tab" data-bs-toggle="tab" data-bs-target="#PreviewButton" type="button" role="tab" aria-controls="PreviewButton" aria-selected="true">Preview </button>
          </li>
          <li class="nav-item" role="presentation">
            <button class="nav-link" id="AngularButton-tab" data-bs-toggle="tab" data-bs-target="#AngularButton" type="button" role="tab" aria-controls="AngularButton" aria-selected="false"><i class="bi bi-code-slash" style="font-size:1.0rem"></i>Angular</button>
          </li>
          <li class="nav-item" role="presentation">
            <button class="nav-link" id="ReactButton-tab" data-bs-toggle="tab" data-bs-target="#ReactButton" type="button" role="tab" aria-controls="ReactButton" aria-selected="false"><i class="bi bi-code-slash" style="font-size:1.0rem"></i>React</button>
          </li>
        </ul>
      </div>
      <div class="tab-content card border" id="myTabContent">
        <div class="tab-pane fade show active" id="PreviewButton" role="tabpanel" aria-labelledby="PreviewButton-tab">
          <div class="contents p-5">
            <div class="row">
              <div class="col-12">
                <img src="/images/badge-as-button.png" class="img-fluid">                               
                  </div>
            </div>
          </div>
        </div>
        <div class="tab-pane fade show" id="AngularButton" role="tabpanel" aria-labelledby="AngularButton-tab">
          <div class="contents bg-code">
<div class="row m-0">

```html
<rds-button [label]="'Button'" [colorVariant]="'primary'" size="medium">
  <rds-badge
    class="ms-2"
    [size]="size"
    [label]="label"
    [colorVariant]="colorVariant"
    [badgeType]="badgeType"
  ></rds-badge>
</rds-button>
```

</div>
          </div>
        </div>
        <!-- React start -->
             <div class="tab-pane fade show" id="ReactButton" role="tabpanel" aria-labelledby="ReactButton-tab">
          <div class="contents bg-code">
<div class="row m-0">

```html
<RdsButton colorVariant="primary" label="Button" type="button">
  <RdsBadge
    badgeType="rectangle"
    colorVariant="danger"
    label="9"
    size="medium"
  />
</RdsButton>
```

</div>
          </div>
        </div>
        <!-- React end -->
      </div>
    </div>
  </section>

<section class="py-4">
    <h6>Icon with overlay</h6>
    <div class="py-3">
      <div class="cust-tabs">
        <ul class="nav nav-tabs" id="myTab" role="tablist">
          <li class="nav-item" role="presentation">
            <button class="nav-link active" id="PreviewIcon-tab" data-bs-toggle="tab" data-bs-target="#PreviewIcon" type="button" role="tab" aria-controls="PreviewIcon" aria-selected="true">Preview </button>
          </li>
          <li class="nav-item" role="presentation">
            <button class="nav-link" id="AngularIcon-tab" data-bs-toggle="tab" data-bs-target="#AngularIcon" type="button" role="tab" aria-controls="AngularIcon" aria-selected="false"><i class="bi bi-code-slash" style="font-size:1.0rem"></i>Angular</button>
          </li>
          <li class="nav-item" role="presentation">
            <button class="nav-link" id="ReactIcon-tab" data-bs-toggle="tab" data-bs-target="#ReactIcon" type="button" role="tab" aria-controls="ReactIcon" aria-selected="false"><i class="bi bi-code-slash" style="font-size:1.0rem"></i>React</button>
          </li>
        </ul>
      </div>
      <div class="tab-content card border" id="myTabContent">
        <div class="tab-pane fade show active" id="PreviewIcon" role="tabpanel" aria-labelledby="PreviewIcon-tab">
          <div class="contents p-5">
            <div class="row">
              <div class="col-12">
                      <img src="/images/badge-with-icon-overlay.png" class="img-fluid">                          
                </div>
            </div>
          </div>
        </div>
        <div class="tab-pane fade show" id="AngularIcon" role="tabpanel" aria-labelledby="AngularIcon-tab">
          <div class="contents bg-light">
<div class="row  text-white m-0 p-4">

```html
<rds-button
  class="position-relative"
  [size]="'small'"
  [id]="'notification'"
  [roundedButton]="true"
  [colorVariant]="'default'"
>
  <rds-icon
    name="notification"
    colorVariant="primary"
    width="20px"
    height="20px"
  ></rds-icon>
  <rds-badge
    [size]="size"
    [label]="label"
    [colorVariant]="colorVariant"
    [badgeType]="badgeType"
    [positioned]="positioned"
  ></rds-badge>
</rds-button>
```

</div>
          </div>
        </div>
        <!-- React start -->
                <div class="tab-pane fade show" id="ReactIcon" role="tabpanel" aria-labelledby="ReactIcon-tab">
          <div class="contents bg-light">
<div class="row  text-white m-0 p-4">

```html
<span className="position-relative">
  <RdsIcon height="33px" name="notification" stroke width="33px" />
  <RdsBadge
    badgeType="circle"
    colorVariant="danger"
    label="9"
    positioned
    size="large"
  />
</span>
```

</div>
          </div>
        </div>
        <!-- React end -->
      </div>
    </div>
  </section>

<section class="py-4">
    <h6>Label with Overlay</h6>
    <div class="py-3">
      <div class="cust-tabs">
        <ul class="nav nav-tabs" id="myTab" role="tablist">
          <li class="nav-item" role="presentation">
            <button class="nav-link active" id="PreviewPositioned-tab" data-bs-toggle="tab" data-bs-target="#PreviewPositioned" type="button" role="tab" aria-controls="PreviewPositioned" aria-selected="true">Preview </button>
          </li>
          <li class="nav-item" role="presentation">
            <button class="nav-link" id="AngularPositioned-tab" data-bs-toggle="tab" data-bs-target="#AngularPositioned" type="button" role="tab" aria-controls="AngularPositioned" aria-selected="false"><i class="bi bi-code-slash" style="font-size:1.0rem"></i>Angular</button>
          </li>
          <li class="nav-item" role="presentation">
            <button class="nav-link" id="ReactPositioned-tab" data-bs-toggle="tab" data-bs-target="#ReactPositioned" type="button" role="tab" aria-controls="ReactPositioned" aria-selected="false"><i class="bi bi-code-slash" style="font-size:1.0rem"></i>React</button>
          </li>
        </ul>
      </div>
      <div class="tab-content card border" id="myTabContent">
        <div class="tab-pane fade show active" id="PreviewPositioned" role="tabpanel" aria-labelledby="PreviewPositioned-tab">
          <div class="contents  p-5">
            <div class="row">
              <div class="col-12">
                  <img src="/images/badge-with-position.png" class="img-fluid">
                                             </div>
            </div>
          </div>
        </div>
        <div class="tab-pane fade show" id="AngularPositioned" role="tabpanel" aria-labelledby="AngularPositioned-tab">
          <div class="contents bg-light">
<div class="row  text-white m-0 p-4">

```html
<rds-button
  [colorVariant]="'primary'"
  size="medium"
  class="position-relative"
  [label]="'button'"
>
  <rds-badge
    [size]="size"
    [label]="label"
    [colorVariant]="colorVariant"
    [badgeType]="badgeType"
    [positioned]="positioned"
  ></rds-badge>
</rds-button>
```

</div>
          </div>
        </div>
        <!-- React start -->
                <div class="tab-pane fade show" id="ReactPositioned" role="tabpanel" aria-labelledby="ReactPositioned-tab">
          <div class="contents bg-light">
<div class="row  text-white m-0 p-4">

```html
<RdsButton
  class="position-relative"
  colorVariant="primary"
  label="Button"
  size="medium"
  type="button"
>
  <RdsBadge
    badgeType="rectangle"
    colorVariant="danger"
    label="99"
    positioned
    size="medium"
  />
</RdsButton>
```

</div>
          </div>
        </div>
      </div>
    </div>
  </section>

<div class="py-4">
<!-- Skeleton / Specifications -->

###### Skeleton / Specifications

<div class="py-3">
 <div class="card border p-5">
  <div class="row">
      <div class="col-md-12">
        <img src="/images/badge-skeleton.png" class="img-fluid">
     </div>
   </div>
   </div>
 </div>
</div>

<!-- JavaScript Bundle with Popper -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
