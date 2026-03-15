<script lang="ts">
  import ArticleList from '$lib/components/ArticleList.svelte';
    import { cat } from './articles';
</script>

<div class="category-page">
  <h1>デジタルケーブル基礎</h1> <!--カテゴリ名を表示-->
  <ArticleList categoryId="02-cat2" /> <!--カテゴリIDで記事の絞り込み-->
  <h1>{cat}</h1>
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