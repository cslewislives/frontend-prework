# Text Layout - Activity

![Text Layout](../../../.gitbook/assets/image%20%2892%29.png)

Using [JSBin](https://jsbin.com/hilococ/1/edit?html,output) follow the instructions below. Please attempt the activity before looking at the solution: 

{% tabs %}
{% tab title="Instructions" %}
**Instructions:**

Using Bootstrap CSS, create a layout that looks like the one shown here. Make sure you add the Bootstrap CDN to your HTML.

![](../../../.gitbook/assets/image%20%2898%29.png)

**Hint:** Spend some time prior to coding on drawing out the grid layout.

**Hint:** Count the number of rows and columns.

**Hint:** Then use the bootstrap grid syntax to code it out.
{% endtab %}

{% tab title="Solution" %}
```markup
<!DOCTYPE html>
<html lang="en-us">

<head>

  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Bootstrap Demo</title>

  <!-- Bootstrap CDN -->
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css">

</head>

<body>
  <!-- Creates the Overall Grid -->
  <div class="container">

    <!-- Row 1 -->
    <div class="row">
      <div class="col-sm-12">
        <h1>Header</h1>
      </div>
    </div>

    <!-- Row 2 -->
    <div class="row">
      <div class="col-sm-3">
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Incidunt optio provident tempora amet, eveniet et, eum illum, culpa laborum dicta recusandae magni architecto. Illo saepe facilis, unde. Debitis, atque, doloremque?</p>
      </div>
      <div class="col-sm-3">
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. At dolorum perferendis voluptates error ullam placeat repellendus. Repellendus error repellat veritatis recusandae voluptates earum rerum consectetur itaque, ipsam nihil. Alias, nemo.</p>
      </div>
      <div class="col-sm-3">
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolores ratione sint ex porro excepturi non dolorum, ullam ea quae vel earum, soluta obcaecati natus. Eligendi iusto accusantium mollitia debitis assumenda!</p>
      </div>
    </div>

    <!-- Row 3 -->
    <div class="row">
      <div class="col-sm-2">
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consequuntur optio dolorem dolores odio alias perferendis, commodi cum. Natus libero cum dolore officia quia eveniet modi reprehenderit soluta ratione quisquam? Sequi.</p>
      </div>
      <div class="col-sm-2">
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consequuntur optio dolorem dolores odio alias perferendis, commodi cum. Natus libero cum dolore officia quia eveniet modi reprehenderit soluta ratione quisquam? Sequi.</p>
      </div>
      <div class="col-sm-2">
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consequuntur optio dolorem dolores odio alias perferendis, commodi cum. Natus libero cum dolore officia quia eveniet modi reprehenderit soluta ratione quisquam? Sequi.</p>
      </div>
      <div class="col-sm-2">
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consequuntur optio dolorem dolores odio alias perferendis, commodi cum. Natus libero cum dolore officia quia eveniet modi reprehenderit soluta ratione quisquam? Sequi.</p>
      </div>
      <div class="col-sm-2">
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consequuntur optio dolorem dolores odio alias perferendis, commodi cum. Natus libero cum dolore officia quia eveniet modi reprehenderit soluta ratione quisquam? Sequi.</p>
      </div>
      <div class="col-sm-2">
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consequuntur optio dolorem dolores odio alias perferendis, commodi cum. Natus libero cum dolore officia quia eveniet modi reprehenderit soluta ratione quisquam? Sequi.</p>
      </div>
    </div>

    <!-- Row 4 -->
    <div class="row">
      <div class="col-sm-6">
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Deleniti illo voluptates blanditiis nisi! Ullam dolore aspernatur, ratione error similique veniam iusto, labore repellat eaque nostrum optio doloribus illo nihil dolor?</p>
      </div>
      <div class="col-sm-6">
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Commodi sequi ex quam quia iste, nemo molestias dolor, qui dolorem voluptatibus ipsa maxime voluptas et deserunt porro repellendus veritatis nesciunt quisquam.</p>
      </div>
    </div>
  </div>

</body>

</html>
```
{% endtab %}

{% tab title="Solution Video Guide" %}
Video Guide:

{% embed url="https://www.youtube.com/watch?v=wQovwgW020g" %}
{% endtab %}
{% endtabs %}
