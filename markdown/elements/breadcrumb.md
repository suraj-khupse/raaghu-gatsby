---
slug: "/breadcrumb"
date: "2019-05-04"
title: "Elements > Breadcrumb"
---

<!-- CSS only -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
<link rel="stylesheet" href="../assets/css/style-elements.css">
<link rel="stylesheet" href="../assets/css/main.css">

#### Breadcrumb

<p class="">Breadcrumbs are a list of links representing the current page and its "ancestors".</p>
<section class="py-4">
    <h6>Default</h6>
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
         <div class="contents p-5">
              <div class="row">
                 <div class="col-md-12">
                     <img src="/images/breadcrumb-divider.png" class="img-fluid">
                 </div>            
           </div>
                       
  </div>
        </div>
        <div class="tab-pane fade show" id="AngularBasic" role="tabpanel" aria-labelledby="AngularBasic-tab">
          <div class="contents bg-code">
<div class="row m-0">

```html
<rds-breadcrumb
  [breadcrumbsItems]="breadcrumbsItems"
  role="basic"
></rds-breadcrumb>
```
</div>
</div>
  </div>
  <!-- React start -->

  <div class="tab-pane fade show" id="ReactBasic" role="tabpanel" aria-labelledby="ReactBasic-tab">
    <div class="contents bg-code">

<div class="row m-0">

```html
<RdsBreadcrumb
  breadItems={[
    {
      active: false,
      disabled: false,
      icon: 'home',
      iconColor: 'primary',
      iconFill: false,
      iconHeight: '15px',
      iconWidth: '15px',
      iconstroke: true,
      id: 1,
      label: 'Home',
      route: '#'
    },
    {
      active: false,
      disabled: false,
      icon: 'information',
      iconColor: 'primary',
      iconFill: false,
      iconHeight: '15px',
      iconWidth: '15px',
      iconstroke: true,
      id: 2,
      label: 'About',
      route: '#'
    },
    {
      active: false,
      disabled: true,
      icon: 'phone',
      iconColor: 'primary',
      iconFill: false,
      iconHeight: '15px',
      iconWidth: '15px',
      iconstroke: true,
      id: 3,
      label: 'Contact'
    }
  ]}
  role="advance"
/>
```

</div>
          </div>
        </div>
        <!-- React end -->
        </div>
      </div>
    </div>
  </section>
   

   <!-- <section class="py-4">
    <h6>Advanced</h6>
    <div class="py-3">
      <div class="cust-tabs">
        <ul class="nav nav-tabs" id="myTab" role="tablist">
          <li class="nav-item" role="presentation">
            <button class="nav-link active" id="PreviewBasic-tab" data-bs-toggle="tab" data-bs-target="#PreviewBasic" type="button" role="tab" aria-controls="PreviewBasic" aria-selected="true">Preview </button>
          </li>
          <li class="nav-item" role="presentation">
            <button class="nav-link" id="AngularBasic-tab" data-bs-toggle="tab" data-bs-target="#AngularBasic" type="button" role="tab" aria-controls="AngularBasic" aria-selected="false"><i class="bi bi-code-slash" style="font-size:1.0rem"></i>Angular</button>
          </li>
        </ul>
      </div>
      <div class="tab-content card border" id="myTabContent">
        <div class="tab-pane fade show active" id="PreviewBasic" role="tabpanel" aria-labelledby="PreviewBasic-tab">
         <div class="contents p-5">
              <div class="row">
                 <div class="col-md-12">
                     <img src="/images/breadcrumb-advanced.png" class="img-fuild">
                 </div>            
           </div>
                       
  </div>
        </div>
        <div class="tab-pane fade show" id="AngularBasic" role="tabpanel" aria-labelledby="AngularBasic-tab">
          <div class="contents bg-code">
<div class="row m-0">

```html
  <rds-breadcrumb
  [customBreadcrumbsItems]="customBreadcrumbsItems"
  role="Advanced"
  [iconShow]="true"
></rds-breadcrumb>
```
</div>
</div>
  </div>
        </div>
      </div>
    </div>
  </section> -->

   <!-- <section class="py-4">
    <h6>With Divider</h6>
    <div class="py-3">
      <div class="cust-tabs">
        <ul class="nav nav-tabs" id="myTab" role="tablist">
          <li class="nav-item" role="presentation">
            <button class="nav-link active" id="PreviewDivide-tab" data-bs-toggle="tab" data-bs-target="#PreviewDivide" type="button" role="tab" aria-controls="PreviewDivide" aria-selected="true">Preview </button>
          </li>
          <li class="nav-item" role="presentation">
            <button class="nav-link" id="AngularDivide-tab" data-bs-toggle="tab" data-bs-target="#AngularDivide" type="button" role="tab" aria-controls="AngularDivide" aria-selected="false"><i class="bi bi-code-slash" style="font-size:1.0rem"></i>Angular</button>
          </li>
        </ul>
      </div>
      <div class="tab-content card border" id="myTabContent">
        <div class="tab-pane fade show active" id="PreviewDivide" role="tabpanel" aria-labelledby="PreviewDivide-tab">
         <div class="contents p-5">
              <div class="row">
                 <div class="col-md-12">
                     <img src="/images/breadcrumb-divider.png" class="img-fuild">
                 </div>            
           </div>
                       
  </div>
        </div>
        <div class="tab-pane fade show" id="AngularDivide" role="tabpanel" aria-labelledby="AngularDivide-tab">
          <div class="contents bg-code">
<div class="row m-0">

```html
  <rds-breadcrumb
  [customBreadcrumbsItems]="customBreadcrumbsItems"
  role="withDivider"
  [iconShow]="true"
></rds-breadcrumb>
```
</div>
</div>
  </div>
        </div>
      </div>
    </div>
  </section> -->

###### Skeleton / Specifications 

<div class="py-3">
 <div class="card border p-5">
  <div class="row">
      <div class="col-md-12">
        <img src="/images/breadcrumb-skeleton.png" class="img-fluid">
     </div>
   </div>
   </div>
 </div>
</div>