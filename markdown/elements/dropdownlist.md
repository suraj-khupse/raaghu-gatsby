---
slug: "/dropdownlist"
date: "2019-05-04"
title: "Elements > Dropdownlist"
---

<!-- CSS only -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
<link rel="stylesheet" href="../../../../../../../raaghu/src/assets/css/style-elements.css">
<link rel="stylesheet" href="../../../../../../../raaghu/src/assets/css/main.css">

#### Dropdown List

<p class="checkbox-def">Dropdown list is a blocked dropdown containing the list of contents.</p>

<section class="py-4">
    <h6>Default</h6>
    <div class="py-3">
      <div class="cust-tabs">
        <ul class="nav nav-tabs" id="myTab" role="tablist">
          <li class="nav-item" role="presentation">
            <button class="nav-link active" id="PreviewBasic-tab" data-bs-toggle="tab" data-bs-target="#PreviewBasic" type="button" role="tab" aria-controls="PreviewBasic" aria-selected="true">Preview </button>
          </li>
          <li class="nav-item" role="presentation">
            <button class="nav-link" id="AngularBasic-tab" data-bs-toggle="tab" data-bs-target="#AngularBasic" type="button" role="tab" aria-controls="AngularBasic" aria-selec0ted="false"><i class="bi bi-code-slash" style="font-size:1.0rem"></i>Angular</button>
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
                  <img src="/images/dropdown-list-default.png" class="img-fluid w-100">
               </div>               
              </div>
                       
  </div>
        </div>
        <div class="tab-pane fade show" id="AngularBasic" role="tabpanel" aria-labelledby="AngularBasic-tab">
          <div class="contents bg-code">
<div class="row m-0">

```html
<rds-dropdownlist
  [listItems]="listItems"
  [placeholder]="placeholder"
  [size]="size"
  [multiSelect]="multiSelect"
  [icon]="icon"
  [iconWidth]="iconWidth"
  [iconHeight]="iconHeight"
  [borderDropdown]="borderDropdown"
  [dropdownHeight]="dropdownHeight"
></rds-dropdownlist>
```
</div>
</div>
  </div>
  <!-- React start -->

  <div class="tab-pane fade show" id="ReactBasic" role="tabpanel" aria-labelledby="ReactBasic-tab">
    <div class="contents bg-code">

<div class="row m-0">

```html
<RdsDropdownList
  borderDropdown
  listItems={[
    {
      iconHeight: '20px',
      iconWidth: '20px',
      label: 'EN(US)',
      val: 'en'
    },
    {
      iconHeight: '20px',
      iconWidth: '20px',
      label: 'English(IND)',
      val: 'en'
    },
    {
      iconHeight: '20px',
      iconWidth: '20px',
      label: 'Français',
      val: 'fr'
    },
    {
      iconHeight: '20px',
      iconWidth: '20px',
      label: 'Deutsch',
      val: 'de'
    },
    {
      iconHeight: '20px',
      iconWidth: '20px',
      label: 'Português (Brasil)',
      val: 'pt-BR'
    },
    {
      iconHeight: '20px',
      iconWidth: '20px',
      label: 'Türkçe',
      val: 'tr'
    },
    {
      iconHeight: '20px',
      iconWidth: '20px',
      label: 'Italiano',
      val: 'it'
    }
  ]}
  placeholder="Filter"
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
    <h6>With Offset</h6>
    <div class="py-3">
      <div class="cust-tabs">
        <ul class="nav nav-tabs" id="myTab" role="tablist">
          <li class="nav-item" role="presentation">
            <button class="nav-link active" id="PreviewBasic-tab" data-bs-toggle="tab" data-bs-target="#PreviewBasic" type="button" role="tab" aria-controls="PreviewBasic" aria-selected="true">Preview </button>
          </li>
          <li class="nav-item" role="presentation">
            <button class="nav-link" id="AngularBasic-tab" data-bs-toggle="tab" data-bs-target="#AngularBasic" type="button" role="tab" aria-controls="AngularBasic" aria-selec0ted="false"><i class="bi bi-code-slash" style="font-size:1.0rem"></i>Angular</button>
          </li>
        </ul>
      </div>
      <div class="tab-content card border" id="myTabContent">
        <div class="tab-pane fade show active" id="PreviewBasic" role="tabpanel" aria-labelledby="PreviewBasic-tab">
         <div class="contents p-5">
              <div class="row">
               <div class="col-md-12">
                  <img src="/images/dropdown-list-with-offset.png" class="img-fluid w-100">
               </div>               
              </div>
                       
  </div>
        </div>
        <div class="tab-pane fade show" id="AngularBasic" role="tabpanel" aria-labelledby="AngularBasic-tab">
          <div class="contents bg-code">
<div class="row m-0">

```html
<rds-dropdownlist
  [listItems]="listItems"
  [placeholder]="placeholder"
  [size]="size"
  [multiSelect]="multiSelect"
  [xOffset]="xOffset"
  [yOffset]="yOffset"
  [borderDropdown]="borderDropdown"
  [dropdownHeight]="dropdownHeight"
></rds-dropdownlist>
```
</div>
</div>
  </div>
        </div>
      </div>
    </div>
  </section>



 
<section class="py-4">
                        <h6>
                           Skeleton / Specifications
                        </h6>
                        <div class="py-3">
                              <!-- Tab panes -->
                              <div class="card border p-5">
                                 <div class="row">
                                    <div class="col-md-12">
                                       <img src="/images/dropdown-list-skeleton.png" class="img-fluid">
                                    </div>
                                  </div>
                              </div>
                        </div>
                     </section>




<!-- JavaScript Bundle with Popper -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
