<template>
    <div id="overview">
        <section class="section-colors">
      <h1 class="section__header">Colors</h1>
      <div class="color__container">
        <div class="color__type">
          <h2 class="color__type__header">Primary</h2>
          <div class="color-sample color-sample--primary-light">
            <h3 class="color-sample__text">Light</h3>
          </div>
          <div class="color-sample color-sample--primary">
            <h3 class="color-sample__text">Normal</h3>
          </div>
          <div class="color-sample color-sample--primary-dark">
            <h3 class="color-sample__text">Dark</h3>
          </div>
        </div>
         <div class="color__type">
          <h2 class="color__type__header">Secondary</h2>
          <div class="color-sample color-sample--secondary-light">
            <h3 class="color-sample__text">Light</h3>
          </div>
          <div class="color-sample color-sample--secondary">
            <h3 class="color-sample__text">Normal</h3>
          </div>
          <div class="color-sample color-sample--secondary-dark">
            <h3 class="color-sample__text">Dark</h3>
          </div>
        </div>
        <div class="color__type">
          <h2 class="color__type__header">Tertiary</h2>
          <div class="color-sample color-sample--tertiary-light">
            <h3 class="color-sample__text">Light</h3>
          </div>
          <div class="color-sample color-sample--tertiary">
            <h3 class="color-sample__text">Normal</h3>
          </div>
          <div class="color-sample color-sample--tertiary-dark">
            <h3 class="color-sample__text">Dark</h3>
          </div>
        </div>
        <div class="color__type">
          <h2 class="color__type__header">Status</h2>
          <div class="color-sample color-sample--success">
            <h3 class="color-sample__text">Success</h3>
          </div>
          <div class="color-sample color-sample--warning">
            <h3 class="color-sample__text">Warning</h3>
          </div>
          <div class="color-sample color-sample--error">
            <h3 class="color-sample__text">Error</h3>
          </div>
        </div>
        <div class="color__type color__type--grey">
          <h2 class="color__type__header">Greys</h2>
          <div class="color-sample color-sample--grey-light-1">
            <h3 class="color-sample__text color-sample__text--black">Light 1</h3>
          </div>
          <div class="color-sample color-sample--grey-light-2">
            <h3 class="color-sample__text color-sample__text--black">Light 2</h3>
          </div>
          <div class="color-sample color-sample--grey-light-3">
            <h3 class="color-sample__text color-sample__text--black">Light 3</h3>
          </div>
          <div class="color-sample color-sample--grey-dark-1">
            <h3 class="color-sample__text">Dark 1</h3>
          </div>
          <div class="color-sample color-sample--grey-dark-2">
            <h3 class="color-sample__text">Dark 2</h3>
          </div>
          <div class="color-sample color-sample--grey-dark-3">
            <h3 class="color-sample__text">Dark 3</h3>
          </div>
        </div>
      </div>
    </section>

    <section class="section-text">
      <h1 class="section__header">Text</h1>
      <div class="text-container">
        <h1>Heading-Primary</h1>
        <h1 class="text--white">Heading-Primary White</h1>
        <h1 class="text--black">Heading-Primary Black</h1>
        <h1 class="text--gradient">Heading-Primary Gradient</h1>
        <h2>Heading-Secondary</h2>
        <h2 class="text--white">Heading-Secondary White</h2>
        <h2 class="text--black">Heading-Secondary Black</h2>
        <h2 class="text--gradient--seconary">Heading-Secondary Gradient</h2>
        <h3>Heading-Tertiary</h3>
        <h3 class="text--white">Heading-Tertiary White</h3>
        <h3 class="text--black">Heading-Tertiary Black</h3>
        <p>Paragraph</p>
        <p class="text--black">Paragraph Black</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus, quisquam. Molestiae cupiditate 
          unde minus a facere illum vero tenetur pariatur. Rem praesentium quas aspernatur a! Architecto alias nobis quisquam labore!</p>
      </div>
    </section>

    <section class="section-components">
      <h1 class="section__header">Components</h1>
      <div class="components-container">
        <div class="component__type">
            <h2 class="component__type__header">Buttons</h2>
            <div class="component__type__items">
              <div class="btn">Normal</div>
              <div class="btn btn--white">
                <div class="btn-text">White</div>
              </div>
              <div class="btn btn--primary">Primary</div>
              <div class="btn btn--secondary">Secondary</div>
              <div class="btn btn--gradient">Gradient</div>
            </div>
        </div>
        <div class="component__type">
          <h2 class="component__type__header">Form</h2>
          <div class="component__type__items">
            <div class="form">
              <div class="form__group">
                <div class="form__label">Text</div>
                <input type="text" class="form__input" placeholder="Dark Text Input">
                <input type="text" class="form__input form__input--light" placeholder="Light Text Input">
                <input type="text" class="form__input form__error" placeholder="Error Text Input">
              </div>
              <div class="form__group">
                <div class="form__label">Radio</div>
                <div class="form__radio-group">
                    <input type="radio" class="form__radio-input" id="small" name="size">
                    <label for="small" class="form__radio-label">
                        <span class="form__radio-button"></span>
                        Option 1
                    </label>
                </div>

                <div class="form__radio-group">
                    <input type="radio" class="form__radio-input" id="large" name="size">
                    <label for="large" class="form__radio-label">
                        <span class="form__radio-button"></span>
                        Option 2
                    </label>
                </div>
            </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    </div>
</template>

<script>
export default {
    
}
</script>