<script lang="ts">
  import ArticleList from '$lib/components/ArticleList.svelte';
</script>

<div class="category-page">
  <h1>音声技術Ⅰ（基礎）</h1> <!--h1にカテゴリnameを入力-->
  <ArticleList categoryId="03-StudioOne" /> <!--categoryIdにカテゴリidを入力-->
</div>

<style>
  .category-page {
    padding: 2rem;
  }

  .category-page h1 {
    margin-bottom: 2rem;
    color: #003160;
  }
</style>
