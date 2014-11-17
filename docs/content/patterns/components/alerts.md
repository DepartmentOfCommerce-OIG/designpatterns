---
title: "Alerts and Notifications"
---

[pattern]
### Contextual alerts

Contextual alerts are positioned in relation to some area/form on the page. They may or may not contain action buttons, depending on the situation.

- __Info__ alerts can be used when there are tips/information that a user can benefit from. 
- __Success__ alerts can be used when an action was performed successfully.
- __Warning__ alerts can be used when an action is out of the ordinary or might not be desired.
- __Danger__ alerts can be used when the system has failed to perform an action, or when the user has made an error. 

[preview]
<div style="max-width: 450px;">
    <div class="alert alert-warning">
        <button type="button" class="close" ><span aria-hidden="true">&times;</span><span class="sr-only">Close</span></button>
        <strong>Warning!</strong> There are more than <strong>10</strong> cases assigned to <strong>John</strong>.
    </div>
    <div class="alert alert-success">
        <a href="" class="alert-link pull-right">Undo</a>
        <strong>Success:</strong> Case assigned to <strong>Jerry</strong>.
    </div>
    <div class="alert alert-info">
        <button type="button" class="close" ><span aria-hidden="true">&times;</span><span class="sr-only">Close</span></button>
        <strong>Info:</strong> Press the <strong>'A'</strong> key to automatically assign a case.
    </div>
    <div class="alert alert-danger">
        <a href="" class="alert-link pull-right">Retry</a>
        <strong>Whoops!</strong> There was a network error assigning case <strong>90/934,382</strong>. 
    </div>
    <div class="alert alert-danger">
        <strong>Whoops!</strong> Please fix the 3 errors.
    </div>
</div>
[/preview]

```html
<div class="alert alert-warning">
    <button type="button" class="close" ><span aria-hidden="true">&times;</span><span class="sr-only">Close</span></button>
    <strong>Warning!</strong> There are more than <strong>10</strong> cases assigned to <strong>John</strong>.
</div>
<div class="alert alert-success">
    <a href="" class="alert-link pull-right">Undo</a>
    <strong>Success:</strong> Case assigned to <strong>Jerry</strong>.
</div>
<div class="alert alert-info">
    <button type="button" class="close" ><span aria-hidden="true">&times;</span><span class="sr-only">Close</span></button>
    <strong>Info:</strong> Press the <strong>'A'</strong> key to automatically assign a case.
</div>
<div class="alert alert-danger">
    <a href="" class="alert-link pull-right">Retry</a>
    <strong>Whoops!</strong> There was a network error assigning case <strong>90/934,382</strong>. 
</div>
<div class="alert alert-danger">
    <strong>Whoops!</strong> Please fix the 3 errors.
</div>
```
[/pattern]

[pattern]
### System alerts

System alerts aren't placed in relation with any particular context and float in one in a corner of the screen.

[preview]
<div style="max-width: 400px; margin-bottom: 20px;">
    <div class="toast toast-success">
        <div class="toast-content">
            <button class="close">
                <span>×</span>
            </button>
            <span>Your settings have been saved.</span>
        </div>
    </div>
</div>

<div style="max-width: 400px; margin-bottom: 20px;">
    <div class="toast toast-info">
        <div class="toast-content">
            <button class="close">
                <span>×</span>
            </button>
            <span>Jerry added a comment to one of your cases (90/098,881).</span>
        </div>
        <div class="toast-actions">
            <button type="button" class="btn btn-default">View comment</button> 
        </div>
    </div>
</div>
<div style="max-width: 400px; margin-bottom: 20px;">
    <div class="toast toast-warning">
        <div class="toast-content">
            <button type="button" class="close">
                <span>×</span>
            </button>
            <span>Case 90/842,381 is due tomorrow.</span>
        </div>
        <div class="toast-actions">
            <button type="button" class="btn btn-default">View case</button> 
            <button type="button" class="btn btn-default">Snooze <span class="caret"></span></button> 
        </div>
    </div>
</div>
<div style="max-width: 400px; margin-bottom: 20px;">
    <div class="toast toast-danger">
        <div class="toast-content">
            <button type="button" class="close">
                <span>×</span>
            </button>
            <span>Connection has been lost. Retrying in 30 seconds.</span>
        </div>
        <div class="toast-actions">
            <button type="button" class="btn btn-default">Retry now</button> 
        </div>
    </div>
</div>
[/preview]

```html

```
[/pattern]