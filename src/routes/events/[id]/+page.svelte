<script>
  import { page } from "$app/stores";
  import HeaderPost from "$lib/components/HeaderPost.svelte";
  import postImg1 from "$lib/posts/post1/postImg1.png";
</script>

<!-- TO DO: Need to remove or reduce the size of
    "Rad Institute" on the single post page -->

<!-- TO DO: Would also like to wrap the body of
    every page in a unique id so I can 
    style the each page separately if needed -->

<HeaderPost />
<div id="post">
  <h1 class="title">{$page.params.id}</h1>
  <!-- TO DO: this repeating background image should be dynamic.
    so it should show the category's background image -->

  <div id="meta-data">
    <div class="date">May 25 2022</div>
    <div id="authors">
      <span>Joanna Pope</span>
      <span>Aaron Z. Lewis</span>
      <span>Laura Lotti</span>
    </div>
  </div>

  <div id="post-content">
    <p>
      WIIIIIITTTHHHH so few affordances for taking action on the protocol itself,
      community energy has gravitated towards web3’s ecosystem-wide issues like
      L2 scaling solutions and mechanisms for multi-chain governance. But in
      order for projects in this domain to be successful, Uniswap governance
      needs more off-chain organizational structures and processes to facilitate
      coordination across the complex web of stakeholders. We explore the
      multidimensional nature of this problem and propose potential pathways
      forward.
    </p>

    <blockquote>
      “Other Internet embarked on a listening tour with a diverse set of Uniswap
      stakeholders during the first quarter of 2022. Our aim was to identify the
      most pressing issue areas within the Uniswap community and provide ideas
      to improve protocol governance.”
    </blockquote>

    <div class="image">
      <img src={postImg1} alt="The project image" />
      <div class="caption">
        We compare human ratings of AI-written summaries between a control group
        receiving no assistance and an assisted group who get to see 8
        AI-written critiques. Summaries are picked from 3 different sources.
        Assisted humans find about 50% more flaws in summaries than unassisted
        raters, using model critiques directly for most of the critiques they
        find.
      </div>
    </div>

    <hr />

    <h1>Experiments with AI assistance</h1>

    <p>
      Other existing approaches frequently use smaller, more closely paired
      audio-text training datasets,<a class="footnote">123</a> or use broad but unsupervised
      audio pretraining.456 Because Whisper was trained on a large and diverse dataset
      and was not fine-tuned to any specific one, it does not beat models that specialize
      in LibriSpeech performance, a famously competitive benchmark in speech recognition.
      However, when we measure Whisper’s zero-shot performance across many diverse
      datasets we find it is much more robust and makes 50% fewer errors than those
      models.
    </p>

    <h2>Do models tell us everything they know?</h2>

    <p>
      To mitigate this problem, we want to train AI assistants that help humans
      provide feedback on hard tasks. These assistants should point out flaws,
      help humans understand what’s going on, and answer their questions. An
      example of this is our past work on book summarization: reading the entire
      book is a lot of work, but humans assisted with chapter summaries have a
      much easier time evaluating a book summary.
    </p>

    <p>
      We want to ensure that future AI systems performing very difficult tasks
      remain aligned with human intent. Many previous works on aligning language
      models rely on human evaluations as a training signal. However, humans
      struggle at evaluating very difficult tasks—for example, it is hard to
      spot every bug in a codebase or every<a class="footnote">18</a> factual error
      in a long essay. Models may then learn to give outputs that look good to humans
      but have errors we systematically fail to notice.
    </p>

    <p>
      To mitigate this problem, we want to train AI assistants that help humans
      provide feedback on hard tasks. These assistants should point out flaws,
      help humans understand what’s going on, and answer their questions. An
      example of this is our past work on book summarization: reading the entire
      book is a lot of work, but humans assisted with chapter summaries have a
      much easier time evaluating a book summary.
    </p>
    <ul>
      <li>As a proof of concept, we use supervised learning.</li>
      <li>To train language models to write critiques of</li>
      <li>
        Topic-based summaries<a class="footnote">91</a> of short stories, Wikipedia
        articles, and other texts from the internet
      </li>
      <ul>
        <li>We use these models to assist</li>
        <li>Human evaluators and study scaling properties</li>
        <ul>
          <li>To mitigate this problem, we want to train AI</li>
          <li>Much easier time evaluating a book summary</li>
        </ul>
        <li>These assistants should point out flaws</li>
      </ul>
      <li>what’s going on, and answer their questions</li>
    </ul>

    <!-- TO DO:
    - Add h3
    - add footer with references
    - link references from links above to the footer
    - code block
    - numbered list
    - paragraph-width image
    - link style -->
  </div>
</div>
<!-- closes post -->

<style>
  
</style>

