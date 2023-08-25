
# ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/core/images/project_color_16x16.png?raw=true "Project") sample_segment

How to use Segment container component

<details><summary><span style="color:DarkGoldenRod"><i>Connectors</i></span></summary><blockquote><p>


## ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/connectors/images/sqlconnector_color_16x16.png?raw=true "SqlConnector") void

void connector, replace or don't use it

<details><summary><span style="color:DarkGoldenRod"><i>Transactions</i></span></summary><blockquote><p>


### ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/transactions/images/sqltransaction_color_16x16.png?raw=true "SqlTransaction") void

does nothing
</p></blockquote></details>
</p></blockquote></details>

<details><summary><span style="color:DarkGoldenRod"><i>Mobile Application</i></span></summary><blockquote><p>


## ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/core/images/mobileapplication_color_16x16.png?raw=true "MobileApplication") Application

Segment container and segment buttons usage

<details><summary><span style="color:DarkGoldenRod"><i>Pages</i></span></summary><blockquote><p>


### ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/pagecomponent_color_16x16.png?raw=true "PageComponent") Page

<ul>
<li>In the <b>pageDidEnter</b> event, a local variable '<b>option</b>' is set with value 1.</li>
<li>In the page Header, a <b>Segment container</b> bound to the local variable 'option' is added.</li>
<li>2 <b>Segment buttons</b> are added with <b>value</b> property set respectively to 1 and 2.</li>
<li>In the page Content, a <b>Switch Directive</b> is set with 2 <b>SwitchCase</b> whose <b>Directive expression</b> properties are set respectively to 1 and 2 (same as Segment buttons)</li>
<li>All the different page content is added to the different SwitchCase</li>
<li>By clicking the Segment buttons, it will switch between the different SwitchCase components.</li>
</ul>
</p></blockquote></details>
</p></blockquote></details>
