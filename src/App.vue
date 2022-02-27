<script>
export default {
  render(h) {
    return h("div", { class: { 'block w-full h-screen bg-faint' : true } }, [
      h("div", { class: { 'container block w-full max-w-2xl m-auto px-2' : true } }, [
        h("section", { class: { 'bg-white' : true } }, [
          h("header", { class: { 'w-full flex justify-between p-5 border-b border-grey' : true } }, [
            h("div", { class: { 'w-1/3 h-20 bg-black' : true } },),
            h("div", { class: { 'fle flex-col w-1/3 h-20 text-center' : true } },[
              h("h2", { class: { ' text-sm font-medium' : true },},'🦄 Team Unicorns'),
              h("p", { class: { ' text-xs' : true },},'last seen 45 minutes ago'),
            ]

            ),
            h("div", { class: { 'text-right w-1/3 h-20' : true } },[
              h("p", { class: { ' text-3xl text-grey' : true },},'...'),
            ]),
          ])
        ])
      ])
    ])
  }
};
</script>

<style>
@import "./assets/css/style";
</style>
