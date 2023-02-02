---
slug: "/benefit"
date: "2019-05-04"
title: "Elements > Benefit"
---

<!-- CSS only -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
<link rel="stylesheet" href="../../../../../../../raaghu/src/assets/css/style-elements.css">
<link rel="stylesheet" href="../../../../../../../raaghu/src/assets/css/main.css">

#### Benefit

<p class="">Benefit lists the value addition for an user for associating with the webpage.</p>
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
                  <img src="/images/benefit-basic.png" class="img-fuild w-75">
               </div>              
           </div>
                       
  </div>
        </div>
        <div class="tab-pane fade show" id="AngularBasic" role="tabpanel" aria-labelledby="AngularBasic-tab">
          <div class="contents bg-code">
<div class="row m-0">

```html
<rds-benefit [item]="item" display_type="Default"></rds-benefit>

```
</div>
</div>
  </div>
  <!-- React Start -->
  <div class="tab-pane fade show" id="ReactBasic" role="tabpanel" aria-labelledby="ReactBasic-tab">
  <div class="contents bg-code ">
<div class="row text-white m-0 p-4">

```html
    <RdsBenefit
    displayType="default"
    item={{
    description: 'Get your order in 2 days',
    icon: 'currency_dollar_circle',
    iconColorVarient: 'dark',
    iconFill: false,
    iconHeight: '35px',
    iconWidth: '35px',
    iconstroke: true,
    id: 1,
    title: 'International delivery'
  }}
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
   
   <section class="py-4">
    <h6>With Illustrations Centre Align</h6>
    <div class="py-3">
      <div class="cust-tabs">
        <ul class="nav nav-tabs" id="myTab" role="tablist">
          <li class="nav-item" role="presentation">
            <button class="nav-link active" id="PreviewBasic1-tab" data-bs-toggle="tab" data-bs-target="#PreviewBasic1" type="button" role="tab" aria-controls="PreviewBasic" aria-selected="true">Preview </button>
          </li>
          <li class="nav-item" role="presentation">
            <button class="nav-link" id="AngularBasic-tab1" data-bs-toggle="tab" data-bs-target="#AngularBasic1" type="button" role="tab" aria-controls="AngularBasic" aria-selected="false"><i class="bi bi-code-slash" style="font-size:1.0rem"></i>Angular</button>
          </li>
          <li class="nav-item" role="presentation">
            <button class="nav-link" id="ReactBasic-tab" data-bs-toggle="tab" data-bs-target="#ReactCentre" type="button" role="tab" aria-controls="ReactBasic" aria-selected="false"><i class="bi bi-code-slash" style="font-size:1.0rem"></i>React</button>
          </li>
        </ul>
      </div>
      <div class="tab-content card border" id="myTabContent">
        <div class="tab-pane fade show active" id="PreviewBasic1" role="tabpanel" aria-labelledby="PreviewBasic1-tab">
         <div class="contents p-5">
              <div class="row">
                 <div class="col-md-12">
                     <img src="/images/benefit-centre.png" class="img-fuild w-75">
                 </div>              
           </div>
                       
  </div>
        </div>
        <div class="tab-pane fade show" id="AngularBasic1" role="tabpanel" aria-labelledby="AngularBasic-tab1">
          <div class="contents bg-code">
<div class="row m-0">

```html
<rds-benefit [item]="item" display_type="Centre Aligned"></rds-benefit>

```
</div>
</div>
  </div>
  <!-- React Start -->
        <div class="tab-pane fade show" id="ReactCentre" role="tabpanel" aria-labelledby="ReactBasic-tab">
          <div class="contents bg-code ">
<div class="row text-white m-0 p-4">

```html
<RdsBenefit
  displayType="Center Aligned"
  item={{
    description: 'Free delivery is our main part of company we just price it into the products. Someone\'s paying for it, and it\'s not us.',
    icon: 'truck',
    iconColorVarient: 'dark',
    iconFill: false,
    iconHeight: '40px',
    iconWidth: '40px',
    iconstroke: true,
    id: 6,
    title: 'Free shipping'
  }}
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


<!-- With Heading and Label centre align -->

  <section class="py-4">
    <h6>With Heading and Label Centre align</h6>
    <div class="py-3">
      <div class="cust-tabs">
        <ul class="nav nav-tabs" id="myTab" role="tablist">
          <li class="nav-item" role="presentation">
            <button class="nav-link active" id="PreviewBasic-tab2" data-bs-toggle="tab" data-bs-target="#PreviewBasic2" type="button" role="tab" aria-controls="PreviewBasic" aria-selected="true">Preview </button>
          </li>
          <li class="nav-item" role="presentation">
            <button class="nav-link" id="AngularBasic2-tab" data-bs-toggle="tab" data-bs-target="#AngularBasic2" type="button" role="tab" aria-controls="AngularBasic" aria-selected="false"><i class="bi bi-code-slash" style="font-size:1.0rem"></i>Angular</button>
          </li>
           <li class="nav-item" role="presentation">
            <button class="nav-link" id="ReactLabel-tab" data-bs-toggle="tab" data-bs-target="#ReactLabel" type="button" role="tab" aria-controls="ReactLabel" aria-selected="false"><i class="bi bi-code-slash" style="font-size:1.0rem"></i>React</button>
          </li>
        </ul>
      </div>
      <div class="tab-content card border" id="myTabContent">
        <div class="tab-pane fade show active" id="PreviewBasic2" role="tabpanel" aria-labelledby="PreviewBasic2-tab">
         <div class="contents  p-5">
              <div class="row">
                <div class="col-md-12">
                  <img src="/images/benefit-heading.png" class="img-fuild w-25">
                </div>               
           </div>
                       
  </div>
        </div>
        <div class="tab-pane fade show" id="AngularBasic2" role="tabpanel" aria-labelledby="AngularBasic2-tab">
          <div class="contents bg-code">
<div class="row m-0">

```html

<rds-benefit [item]="item" display_type="Heading With Icon"></rds-benefit>

```
</div>
</div>
  </div>
  <!-- React Start -->
        <div class="tab-pane fade show" id="ReactLabel" role="tabpanel" aria-labelledby="ReactLabel-tab">
          <div class="contents bg-code ">
<div class="row text-white m-0 p-4">

```html
<RdsBenefit
  displayType="Center Aligned"
  item={{
    description: 'Free delivery is our main part of company we just price it into the products. Someone\'s paying for it, and it\'s not us.',
    icon: 'truck',
    iconColorVarient: 'dark',
    iconFill: false,
    iconHeight: '40px',
    iconWidth: '40px',
    iconstroke: true,
    id: 6,
    title: 'Free shipping'
  }}
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

  <section class="py-4">
    <h6>With Illustrations Left Aligned</h6>
    <div class="py-3">
      <div class="cust-tabs">
        <ul class="nav nav-tabs" id="myTab" role="tablist">
          <li class="nav-item" role="presentation">
            <button class="nav-link active" id="PreviewBasic3-tab" data-bs-toggle="tab" data-bs-target="#PreviewBasic3" type="button" role="tab" aria-controls="PreviewBasic" aria-selected="true">Preview </button>
          </li>
          <li class="nav-item" role="presentation">
            <button class="nav-link" id="AngularBasic3-tab" data-bs-toggle="tab" data-bs-target="#AngularBasic3" type="button" role="tab" aria-controls="AngularBasic" aria-selected="false"><i class="bi bi-code-slash" style="font-size:1.0rem"></i>Angular</button>
          </li>
          <li class="nav-item" role="presentation">
            <button class="nav-link" id="ReactLeft-tab" data-bs-toggle="tab" data-bs-target="#ReactLeft" type="button" role="tab" aria-controls="ReactLeft" aria-selected="false"><i class="bi bi-code-slash" style="font-size:1.0rem"></i>React</button>
          </li>
        </ul>
      </div>
      <div class="tab-content card border" id="myTabContent">
        <div class="tab-pane fade show active" id="PreviewBasic3" role="tabpanel" aria-labelledby="PreviewBasic3-tab">
         <div class="contents  p-5">
              <div class="row">
                 <div class="col-md-12">
                    <img src="/images/benefit-left-align.png" class="img-fuild w-100">
                 </div>              
           </div>
                       
  </div>
        </div>
        <div class="tab-pane fade show" id="AngularBasic3" role="tabpanel" aria-labelledby="AngularBasic3-tab">
          <div class="contents bg-code">
<div class="row m-0">

```html
<rds-benefit [item]="item" display_type="Left Aligned"></rds-benefit>
```
</div>
</div>
  </div>
   <!-- React Start -->
        <div class="tab-pane fade show" id="ReactLeft" role="tabpanel" aria-labelledby="ReactLeft-tab">
          <div class="contents bg-code ">
<div class="row text-white m-0 p-4">

```html
<RdsBenefit
  displayType="Left Aligned"
  item={{
    description: 'Name another place that offers year long free delivery? We\'ll be waiting. Order now and you\'ll get delivery absolutely free.',
    id: 3,
    imgHeight: '40px',
    imgSrc: 'https://cdn4.vectorstock.com/i/1000x1000/45/38/gear-icon-line-symbol-vector-21084538.jpg',
    imgWidth: '40px',
    title: 'Free delivery all year long'
  }}
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
  <section class="py-4">
    <h6>With Label</h6>
    <div class="py-3">
      <div class="cust-tabs">
        <ul class="nav nav-tabs" id="myTab" role="tablist">
          <li class="nav-item" role="presentation">
            <button class="nav-link active" id="PreviewBasic4-tab" data-bs-toggle="tab" data-bs-target="#PreviewBasic4" type="button" role="tab" aria-controls="PreviewBasic" aria-selected="true">Preview </button>
          </li>
          <li class="nav-item" role="presentation">
            <button class="nav-link" id="AngularBasic4-tab" data-bs-toggle="tab" data-bs-target="#AngularBasic4" type="button" role="tab" aria-controls="AngularBasic" aria-selected="false"><i class="bi bi-code-slash" style="font-size:1.0rem"></i>Angular</button>
          </li>
          <li class="nav-item" role="presentation">
            <button class="nav-link" id="Reactwithlabel-tab" data-bs-toggle="tab" data-bs-target="#Reactwithlabel" type="button" role="tab" aria-controls="Reactwithlabel" aria-selected="false"><i class="bi bi-code-slash" style="font-size:1.0rem"></i>React</button>
          </li>
        </ul>
      </div>
      <div class="tab-content card border" id="myTabContent">
        <div class="tab-pane fade show active" id="PreviewBasic4" role="tabpanel" aria-labelledby="PreviewBasic4-tab">
         <div class="contents  p-5">
              <div class="row">
               <div class="col-md-12">
                   <img src="/images/benefit-with-label.png" class="img-fuild w-100">
               </div>              
           </div>
                       
  </div>
        </div>
        <div class="tab-pane fade show" id="AngularBasic4" role="tabpanel" aria-labelledby="AngularBasic4-tab">
          <div class="contents bg-code">
<div class="row m-0">

```html
<rds-benefit [item]="item" display_type="With Label"></rds-benefit>
```
</div>
</div>
  </div>
          <!-- React Start -->
        <div class="tab-pane fade show" id="Reactwithlabel" role="tabpanel" aria-labelledby="Reactwithlabel-tab">
          <div class="contents bg-code ">
<div class="row text-white m-0 p-4">

```html
<RdsBenefit
  displayType="With Label"
  item={{
    colorVarient: 'success',
    description: 'Name another place that offers year long free delivery? We\'ll be waiting. Order now and you\'ll get delivery absolutely free.',
    id: 7,
    imgHeight: '40px',
    imgSrc: 'https://cdn4.vectorstock.com/i/1000x1000/45/38/gear-icon-line-symbol-vector-21084538.jpg',
    imgWidth: '40px',
    status: 'Active',
    title: 'Free delivery all year long'
  }}
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

<!-- Benefit without Label -->

  <section class="py-4">
    <h6>With Heading and Label Centre Align</h6>
    <div class="py-3">
      <div class="cust-tabs">
        <ul class="nav nav-tabs" id="myTab" role="tablist">
          <li class="nav-item" role="presentation">
            <button class="nav-link active" id="PreviewBasic5-tab" data-bs-toggle="tab" data-bs-target="#PreviewBasic5" type="button" role="tab" aria-controls="PreviewBasic" aria-selected="true">Preview </button>
          </li>
          <li class="nav-item" role="presentation">
            <button class="nav-link" id="AngularBasic5-tab" data-bs-toggle="tab" data-bs-target="#AngularBasic5" type="button" role="tab" aria-controls="AngularBasic" aria-selected="false"><i class="bi bi-code-slash" style="font-size:1.0rem"></i>Angular</button>
          </li>
           <li class="nav-item" role="presentation">
            <button class="nav-link" id="ReactWitoutLabel-tab" data-bs-toggle="tab" data-bs-target="#ReactWitoutLabel" type="button" role="tab" aria-controls="ReactWitoutLabel" aria-selected="false"><i class="bi bi-code-slash" style="font-size:1.0rem"></i>React</button>
          </li>
        </ul>
      </div>
      <div class="tab-content card border" id="myTabContent">
        <div class="tab-pane fade show active" id="PreviewBasic5" role="tabpanel" aria-labelledby="PreviewBasic5-tab">
         <div class="contents  p-5">
              <div class="row">
               <div class="col-md-12">
                   <img src="/images/benefit-without-label.png" class="img-fuild w-50">
               </div>             
           </div>
                       
  </div>
        </div>
        <div class="tab-pane fade show" id="AngularBasic5" role="tabpanel" aria-labelledby="AngularBasic5-tab">
          <div class="contents bg-code">
<div class="row m-0">

```html
  <rds-benefit [item]="item" display_type="Without Label"></rds-benefit>
```
</div>
</div>
  </div>
  <!-- React Start -->
        <div class="tab-pane fade show" id="ReactWitoutLabel" role="tabpanel" aria-labelledby="ReactWitoutLabel-tab">
          <div class="contents bg-code ">
<div class="row text-white m-0 p-4">

```html
<RdsBenefit
  displayType="Without Label"
  item={{
    description: 'Free delivery is our main part of company',
    icon: 'truck',
    iconColorVarient: 'dark',
    iconFill: false,
    iconHeight: '40px',
    iconWidth: '40px',
    iconstroke: true,
    id: 7,
    title: 'Free shipping world wide'
  }}
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
  
  <!-- Skeleton / Specifications -->
<section class="py-4">
                        <h6>
                           Skeleton / Specifications
                        </h6>
                        <div class="py-3">
                              <!-- Tab panes -->
                              <div class="card border p-5">
                                 <div class="row">
                                    <div class="col-md-9 col-12">
                                       <img src="/images/skel-benefit.png" class="img-fluid">
                                    </div>
                                 </div>
                              </div>
                        </div>
                     </section>



<!-- JavaScript Bundle with Popper -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
