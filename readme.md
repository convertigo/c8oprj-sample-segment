


# sample_segment

How to use Segment container component


For more technical informations : [documentation](./project.md)

- [Mobile Application](#mobile-application)
    - [Pages](#pages)
        - [Page](#page)


## Mobile Application

Segment container and segment buttons usage

### Pages

#### Page

<ul>
<li>In the <b>pageDidEnter</b> event, a local variable '<b>option</b>' is set with value 1.</li>
<li>In the page Header, a <b>Segment container</b> bound to the local variable 'option' is added.</li>
<li>2 <b>Segment buttons</b> are added with <b>value</b> property set respectively to 1 and 2.</li>
<li>In the page Content, a <b>Switch Directive</b> is set with 2 <b>SwitchCase</b> whose <b>Directive expression</b> properties are set respectively to 1 and 2 (same as Segment buttons)</li>
<li>All the different page content is added to the different SwitchCase</li>
<li>By clicking the Segment buttons, it will switch between the different SwitchCase components.</li>
</ul>



