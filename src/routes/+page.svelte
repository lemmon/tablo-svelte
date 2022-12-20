<script>
import Section from '$lib/Section.svelte'
import Block from '$lib/Block.svelte'
import Header from '$lib/Header.svelte'
import Copy from '$lib/Copy.svelte'
import Action from '$lib/Action.svelte'
import Button from '$lib/Button.svelte'
import Image from '$lib/Image.svelte'
import Video from '$lib/Video.svelte'
</script>

<Section>
  <Block gap={4}>
    <Header biggest>Welcome to This Beautiful Onepager Website</Header>
    <Copy bigger>
      <p
        >Suspendisse feugiat aliquam arcu ac facilisis. Vestibulum non eros velit. Mauris molestie purus egestas elit
        fermentum porta. Sed et placerat ligula, vel molestie nulla. Phasellus nisl nulla, pulvinar quis finibus eget,
        sollicitudin eu neque. Integer tempus nibh sit amet mi tincidunt rutrum.</p
      >
    </Copy>
    <Action>
      <Button primary href="https://www.github.com/lemmon">Purchase theme</Button>
      <Button href="https://twitter.com/lemmon">Contact me</Button>
    </Action>
  </Block>
  <Block>
    <Image src="https://cloud.4am.sk/data/tablo/demo/3caf6df9-f680-478d-8149-35f337828b1a.960w.webp" ratio="3/4" />
  </Block>
</Section>

<Section>
  <Block>
    <Copy align="center" textalign="center">
      <h2>Well, Hello!</h2>
      <p
        >Phasellus vitae elit feugiat, sollicitudin quam auctor, mattis purus. Suspendisse mattis sollicitudin eros,
        euismod ultricies lorem. In eu lacinia erat. Maecenas efficitur in turpis eu tincidunt. Sed lacinia tincidunt
        orci sit amet varius. Pellentesque non condimentum leo. Integer cursus et elit non volutpat. Proin a ipsum
        ornare, rutrum sapien a, mollis felis.</p
      >
      <p
        >Donec finibus sem ut pulvinar dignissim. Fusce at aliquam augue. Sed mollis purus vitae mauris commodo
        malesuada. Quisque ut tempus magna. Interdum et malesuada fames ac ante ipsum primis in faucibus. Phasellus
        consequat mollis ante, ut dignissim ex aliquet in. Sed interdum lacus vitae odio rhoncus, ullamcorper dapibus
        est sagittis. Suspendisse feugiat aliquam arcu ac facilisis. Vestibulum non eros velit. Mauris molestie purus
        egestas elit fermentum porta.</p
      >
    </Copy>
  </Block>
</Section>

<Section>
  <Block fullwidth>
    <Image
      src="https://cloud.4am.sk/data/tablo/demo/c72d4b1c-e775-4ab7-914b-87e06d086ed9.1280w.webp"
      ratio="8/5"
      caption="Image caption"
    />
  </Block>
  <Block fullwidth>
    <Copy align="center">
      <h2>Heading 2</h2>
      <p
        >Vivamus cursus imperdiet pulvinar. Donec dictum libero tortor, a consectetur nisi pretium et. Quisque id
        aliquet lectus, a laoreet nibh. Nullam hendrerit neque sit amet velit rhoncus tempus. Nunc sagittis eu enim a
        fringilla. Etiam ullamcorper, purus at pellentesque fermentum, ex magna iaculis ex, at mollis erat nunc at elit.
        Sed scelerisque nulla nec nisl molestie consequat. Phasellus vitae elit feugiat, sollicitudin quam auctor,
        mattis purus. Suspendisse mattis sollicitudin eros, euismod ultricies lorem. In eu lacinia erat. Maecenas
        efficitur in turpis eu tincidunt. Sed lacinia tincidunt orci sit amet varius. Pellentesque non condimentum leo.
        Integer cursus et elit non volutpat. Proin a ipsum ornare, rutrum sapien a, mollis felis.</p
      >
      <ul>
        <li>foo</li>
        <li>bar</li>
        <li
          >baz
          <ol>
            <li>first</li>
            <li>second</li>
            <li>third</li>
          </ol>
        </li>
        <li>last</li>
      </ul>
      <pre
        ><code
          ># This is a simple function that prints "Hello, World!" to the console
def say_hello():
    print("Hello, World!")

# Call the function to make it run
say_hello()</code
        ></pre
      >
      <h3>Heading 3</h3>
      <p
        >Etiam ullamcorper, purus at pellentesque fermentum, ex magna iaculis ex, at mollis erat nunc at elit. Sed
        scelerisque nulla nec nisl molestie consequat. Phasellus vitae elit feugiat, sollicitudin quam auctor, mattis
        purus. Suspendisse mattis sollicitudin eros, euismod ultricies lorem. <strong>In eu lacinia erat.</strong> Maecenas
        efficitur in turpis eu tincidunt. Sed lacinia tincidunt orci sit amet varius. Pellentesque non condimentum leo. Integer
        cursus et elit non volutpat. Proin a ipsum ornare, rutrum sapien a, mollis felis.</p
      >
      <blockquote>
        If you set your goals ridiculously high and it's a failure, you will fail above everyone else's success.
        <footer>James Cameron</footer>
      </blockquote>
    </Copy>
  </Block>
  <Block>
    <Video
      src="https://www.youtube.com/embed/R6t73_Y0SEU"
      caption="Stir-fried Pork Liver and Kidney with Chinese Chives"
    />
  </Block>
</Section>
