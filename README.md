Dựa vào các page trên figma, phân tích và tạo ra các file scss tương ứng
scss
  components
    _button.scss        // Define all button styles (primary, icon button, link button, social button, ...)
    _form-control.scss  // Define input control styles
    _header.scss
    _footer.scss
    ....
  pages
    _landing.scss
    _registration.scss
    _login.scss
    _setting.scss
    _dashboard.scss
    _about.scss
    _information.scss
    _course.scss
    _waste.scss
    _product.scss
  _variable.scss      // Define variable
  _mixin.scss         // Define common @mixin
  _reboot.scss        // Reset style, define global default style (body, h1-h6, p)
  _typography.scss    // Define all text styles (trên figma chỉ quan tâm size desktop px)
  ....
  styles.scss         // Import all scss file
landing.html
register.html
login.html
dashboard.html
about.html
information.html
course.html
waste.html
product.html