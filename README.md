# Gazoobie

A flex base responsive CSS framework.

A small code CSS responsive framework based on percentive sizes of twelve columns.

Every container is centered.

Containers can be nested.

**Example: Images in the left box and text on the right. Auto stacks on mobile.**

```
<section class="wrap">
    <div class="container">
        <div class="five column">
            <img src="*" title="[[*pagetitle]]" >
        </div>
        <div class="seven column">
            <h1>[[*pagetitle]]</h1>
                <div class="content">
                    [[*content]]
                </div>          
            <a class="btn" href="[[~11]]" title="Contact [[++site_name]]" >CONTACT ABOUT [[*menutitle]]!</a>
        </div>
    </div>
</section>
```

# Specialty Classes


## Container

- .fullwidth Expands the width of the container
- .justifyleft All columns left
- .justifyright All columns right

## Column

- .card Class to create a basic card with a border, margins, and padding.
- .centerhrz Content centered on the horizontal center
- .centervrt Content centered on the vertical center
