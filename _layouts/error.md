<!DOCTYPE html>
<html lang="{{ site.lang | default: "en-US" }}">
  {% include head.md %}
  <body>
    <div class="main-content">
      {{ content }}
    </div>
    {% include acknowledgments.md %}
    {% include footer.md %}
  </body>
</html>
