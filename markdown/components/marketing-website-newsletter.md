---
slug: "/comp-marketing-website-newsletter"
date: "2019-05-04"
title: "Components > Marketing Website Newsletter"
---
<!-- CSS only -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
<link rel="stylesheet" href="../assets/css/style-elements.css">

#### Marketing Website Newsletter

<p>Provides a card with different buttons as an option selector </p>
<section class="py-4">        
    <h6>With Image</h6>                                                                                     
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
              <img src="/images/marketing-website-newsletter1.png" class="img-fluid w-70">
            </div>
           </div>
                       
  </div>
        </div>
        <div class="tab-pane fade show" id="AngularBasic" role="tabpanel" aria-labelledby="AngularBasic-tab">
          <div class="contents bg-code">
<div class="row m-0">

```html
<rds-comp-marketing-website-newsletter
  templateType="with_image"
></rds-comp-marketing-website-newsletter>
```
</div>
</div>
  </div>
        </div>
      </div>
    </div>
  </section>
  
<section class="py-4">                                                                                             
    <h6>With CTA</h6>
    <div class="py-3">
      <div class="cust-tabs">
        <ul class="nav nav-tabs" id="myTab2" role="tablist">
          <li class="nav-item" role="presentation">
            <button class="nav-link active" id="PreviewBasic-tab2" data-bs-toggle="tab" data-bs-target="#PreviewBasic2" type="button" role="tab" aria-controls="PreviewBasic" aria-selected="true">Preview </button>
          </li>
          <li class="nav-item" role="presentation">
            <button class="nav-link" id="AngularBasic-tab2" data-bs-toggle="tab" data-bs-target="#AngularBasic2" type="button" role="tab" aria-controls="AngularBasic" aria-selected="false"><i class="bi bi-code-slash" style="font-size:1.0rem"></i>Angular</button>
          </li>
        </ul>
      </div>
      <div class="tab-content card border" id="myTabContent2">
        <div class="tab-pane fade show active" id="PreviewBasic2" role="tabpanel" aria-labelledby="PreviewBasic-tab">
         <div class="contents p-5">
              <div class="row">
             <div class="col-md-12">
                <img src="/images/marketing-news-letter2.png" class="img-fluid w-70">
             </div>
           </div>
                       
  </div>
        </div>
        <div class="tab-pane fade show" id="AngularBasic2" role="tabpanel" aria-labelledby="AngularBasic-tab">
          <div class="contents bg-code">
<div class="row m-0">

```html
<rds-comp-marketing-website-newsletter
  templateType="with_CTA"
></rds-comp-marketing-website-newsletter>
```
</div>
</div>
  </div>
        </div>
      </div>
    </div>
  </section>
                
                                                                                                                 
<section class="py-4">                                                                                             
    <h6>With Discount Offer</h6>
    <div class="py-3">
      <div class="cust-tabs">
        <ul class="nav nav-tabs" id="myTab3" role="tablist">
          <li class="nav-item" role="presentation">
            <button class="nav-link active" id="PreviewBasic3-tab3" data-bs-toggle="tab" data-bs-target="#PreviewBasic3" type="button" role="tab" aria-controls="PreviewBasic" aria-selected="true">Preview </button>
          </li>
          <li class="nav-item" role="presentation">
            <button class="nav-link" id="AngularBasic3-tab3" data-bs-toggle="tab" data-bs-target="#AngularBasic3" type="button" role="tab" aria-controls="AngularBasic" aria-selected="false"><i class="bi bi-code-slash" style="font-size:1.0rem"></i>Angular</button>
          </li>
        </ul>
      </div>
      <div class="tab-content card border" id="myTabContent3">
        <div class="tab-pane fade show active" id="PreviewBasic3" role="tabpanel" aria-labelledby="PreviewBasic3-tab">
         <div class="contents  p-5">
              <div class="row">
             <div class="col-md-12">
               <img src="/images/marketing-news-letter3.png" class="img-fluid w-70">
             </div>  
           </div>
                       
  </div>
        </div>
        <div class="tab-pane fade show" id="AngularBasic3" role="tabpanel" aria-labelledby="AngularBasic3-tab">
          <div class="contents bg-code">
<div class="row m-0">

```html
<rds-comp-marketing-website-newsletter
  templateType="with_discount_offer"
></rds-comp-marketing-website-newsletter>
```
</div>
</div>
  </div>
        </div>
      </div>
    </div>
  </section>


<section class="py-4">                                                                                             
    <h6>With Email Input</h6>
    <div class="py-3">
      <div class="cust-tabs">
        <ul class="nav nav-tabs" id="myTab3" role="tablist">
          <li class="nav-item" role="presentation">
            <button class="nav-link active" id="PreviewBasic4-tab4" data-bs-toggle="tab" data-bs-target="#PreviewBasic4" type="button" role="tab" aria-controls="PreviewBasic" aria-selected="true">Preview </button>
          </li>
          <li class="nav-item" role="presentation">
            <button class="nav-link" id="AngularBasic4-tab4" data-bs-toggle="tab" data-bs-target="#AngularBasic4" type="button" role="tab" aria-controls="AngularBasic" aria-selected="false"><i class="bi bi-code-slash" style="font-size:1.0rem"></i>Angular</button>
          </li>
        </ul>
      </div>
      <div class="tab-content card border" id="myTabContent4">
        <div class="tab-pane fade show active" id="PreviewBasic4" role="tabpanel" aria-labelledby="PreviewBasic4-tab">
         <div class="contents  p-5">
              <div class="row">
             <div class="col-md-12">
               <img src="/images/marketing-news-letter4.png" class="img-fluid w-70">
             </div>  
           </div>
                       
  </div>
        </div>
        <div class="tab-pane fade show" id="AngularBasic4" role="tabpanel" aria-labelledby="AngularBasic4-tab">
          <div class="contents bg-code">
<div class="row m-0">

```html

<rds-comp-marketing-website-newsletter
  templateType="with_email_input"
></rds-comp-marketing-website-newsletter>
```
</div>
</div>
  </div>
        </div>
      </div>
    </div>
  </section>

  