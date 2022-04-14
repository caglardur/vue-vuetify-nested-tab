<template>
  <v-col>
    <v-data-table :headers="headers" :items="desserts" :items-per-page="limit" class="elevation-1 overflow-auto data-table-height" :loading="loading" loading-text="Loading... Please wait" :hide-default-footer="hideFooter" dense>
      <template v-slot:body="{ items }">
        <tbody>
          <tr v-for="n in items" :key="n" @click="handleDataFc()">
            <td class="caption">caglar</td>
            <td class="caption">durmus</td>
            <td class="caption">zonguldak</td>
            <td class="caption">izmir</td>
            <td class="caption">ısparta</td>
            <td class="caption">istanbul</td>
          </tr>
        </tbody>
      </template>
    </v-data-table>
    Lorem ipsum, dolor sit amet consectetur adipisicing elit. Molestias suscipit aliquid pariatur dolores autem, velit ratione omnis exercitationem? Ipsam quam voluptatibus nesciunt, adipisci, eaque tempore inventore voluptates deleniti aliquam sit, non consectetur. Delectus minus, incidunt saepe itaque eum praesentium magnam eos quos beatae corrupti. Sapiente sit, quibusdam officia nam modi culpa magnam inventore cumque sed. At dolores asperiores, hic saepe porro facilis voluptate earum sed natus aut soluta reiciendis nisi atque debitis quae dignissimos reprehenderit consequuntur illum iusto. Quia porro aliquam sapiente itaque, voluptas corporis ipsa quas eligendi voluptates impedit voluptate dignissimos in hic laudantium dolorum repellendus, blanditiis officia maiores ad cumque fugiat eaque fugit? Voluptatibus quod, unde doloremque blanditiis recusandae aut itaque praesentium officia vel nemo aliquam odit, eos delectus quibusdam magnam deserunt. Reprehenderit laudantium voluptates obcaecati esse pariatur vel aspernatur nobis? Inventore alias quidem cum, nihil illo beatae nulla ex facere quaerat! Libero fugit velit vero culpa officiis quas accusamus nam sint quia nesciunt ab iste ullam earum a alias tempora modi excepturi illum, laudantium perspiciatis aliquid, voluptates iure? Velit ipsam deleniti ex eligendi accusantium esse nostrum nisi suscipit facilis quam debitis, quod, in fugiat ullam, nihil consequuntur mollitia deserunt. Aspernatur rerum sint illo? Perferendis perspiciatis neque repellat sint, explicabo recusandae beatae odio repudiandae. Laudantium voluptatum modi doloribus similique deleniti aut adipisci praesentium ipsum, beatae, laborum eveniet enim delectus error unde, laboriosam amet excepturi facilis autem totam officia ad atque dolorem iure doloremque. Illum eveniet porro necessitatibus tenetur, voluptates impedit suscipit eum repellendus facere. Placeat reprehenderit sequi quam, ea, provident eius accusamus, consectetur maiores pariatur at earum nemo ratione sunt architecto. Est voluptatibus reiciendis corporis harum aperiam aspernatur fuga nihil veniam excepturi, quis similique quod? Sint eum ipsam iure mollitia. Illum culpa ipsam necessitatibus quaerat dolore. Mollitia id dolorem quas, corrupti placeat nesciunt saepe dolorum non, impedit rerum culpa! Error sapiente ducimus explicabo. Consequatur est earum magnam? Eveniet delectus amet animi rerum quia atque deleniti a, beatae qui autem repellendus quasi laudantium expedita repellat, ipsam exercitationem nulla minima fuga eius voluptates alias ratione dolores recusandae minus? Repudiandae quasi magni nemo distinctio necessitatibus. Sint officiis unde praesentium libero cum! Aliquid, distinctio quis. Harum eos, alias saepe vel laudantium dignissimos dolorem cum eaque voluptates quam officiis porro aspernatur eius iste excepturi consectetur cupiditate dolores minus ratione. Dignissimos, ullam expedita laborum ea eos magni exercitationem aut reprehenderit corporis, quas fugit. Itaque iure sit ex iste dolorum quia doloremque voluptatibus voluptatum, optio nam expedita perferendis at aspernatur! Possimus maiores veritatis necessitatibus culpa iure, at quas consequatur facilis doloremque ducimus corrupti sint quod quae eius neque corporis illo dolor quis totam fugit, soluta quam beatae. Nesciunt corrupti sapiente, atque excepturi ullam non dicta. Distinctio quibusdam natus soluta quam, animi asperiores unde consectetur quaerat nemo molestiae, ratione, ipsam beatae autem! Ab, pariatur accusantium sed odio soluta illum! Veritatis rem officiis quia dolorem unde, id voluptas, quam velit iste consequuntur dolores quaerat harum facere illum! Fugit distinctio expedita mollitia in voluptas aliquid, veniam, atque beatae reprehenderit libero, officiis optio? A ad natus vel sunt neque.
    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iure asperiores debitis fugit rerum dolor! Dolores eveniet commodi necessitatibus velit soluta sunt earum reiciendis autem tempore, quos quis dicta. Cupiditate, sapiente. Eligendi saepe id deleniti, voluptate iste possimus nulla assumenda repudiandae nam dignissimos quam doloremque! Facilis praesentium animi neque expedita, quibusdam est mollitia, cupiditate aperiam nemo velit natus labore laboriosam sunt tempora dolores. Consequuntur totam quibusdam voluptate omnis placeat obcaecati accusamus. Reiciendis magnam quia aut nisi odit, sint molestias consectetur iure asperiores. Architecto commodi laboriosam provident perferendis impedit dolorem maxime quae eaque obcaecati maiores reprehenderit sunt delectus velit praesentium cupiditate quas odio id laudantium recusandae accusamus aperiam, ullam voluptates amet. Cum fugit ut nisi labore dolores! Nemo assumenda nam error reiciendis quidem, molestias consequuntur beatae, iste repellendus veritatis, laboriosam excepturi aspernatur unde earum alias architecto cum? Sit ducimus, fugit, quibusdam ut harum consequuntur expedita nobis voluptates sunt natus, provident id saepe quisquam. At quidem perspiciatis, cum obcaecati eligendi soluta natus quasi numquam placeat adipisci ducimus culpa voluptatum corrupti asperiores officiis sed nostrum, error illum. Facere atque laudantium provident fugit a minima suscipit necessitatibus maxime? Ut quaerat minima adipisci, eligendi officiis consequatur, placeat dolores quo vero sed dicta voluptatibus quia excepturi doloribus. Saepe, ratione, officiis ipsam labore alias quaerat nam laboriosam repudiandae, incidunt distinctio modi unde minus ipsum inventore obcaecati! Dolore autem voluptatem quo officia nesciunt quidem expedita, vitae laborum, recusandae repudiandae, praesentium aperiam? Minus rerum tempora earum quasi debitis placeat amet impedit numquam vitae reprehenderit tenetur error laudantium, porro quia, optio vel quidem aliquam quaerat sint nisi. Aspernatur quas sequi eius illum ducimus eligendi? Perferendis, eaque rem modi quo sapiente nemo distinctio deserunt ab iusto sed eum accusantium dolor, minus quasi inventore laudantium temporibus impedit suscipit quos ad expedita, illo nobis. Dolorem sequi rerum porro in minus cumque quod dolore reprehenderit dolor error maiores obcaecati, necessitatibus nesciunt non a! Eius fuga voluptas non repellat ex libero consectetur nemo, iusto molestiae at id maiores, quia repudiandae doloremque accusantium veniam rem a? Molestias est nam et! Voluptatum veniam illo rem qui asperiores quos earum placeat minus? Distinctio atque dolor odio ea saepe officia sapiente eveniet nostrum ullam ad quibusdam amet, dolorem, debitis nihil explicabo repellendus reiciendis voluptas, natus nulla beatae veniam asperiores nesciunt. Animi corrupti maxime totam ipsam quae itaque, quo molestiae ex possimus sit vel. Dolores porro assumenda aliquam quia? Nulla, ab aut nisi nobis eveniet dignissimos. Repellat porro aperiam molestias recusandae totam rerum blanditiis ducimus suscipit molestiae! Dolorem fugit unde explicabo et est doloribus ab eligendi cum. Possimus ducimus, dignissimos fuga quasi et nisi quae, repudiandae modi dolore ipsum, ea error doloribus! Iste commodi et eius cum rerum corporis quam temporibus numquam, nemo saepe blanditiis illum tenetur! Veritatis repudiandae placeat totam, eius, deleniti quasi hic quis voluptatum dolorem, cum fugiat molestias vero iste exercitationem aliquid? Itaque alias laborum rerum! Nemo nam hic esse, laudantium consequatur facilis amet maiores enim inventore nihil corrupti corporis fuga culpa accusamus explicabo veritatis expedita odit quam cupiditate tempore ipsam. Hic similique quidem libero odio at nesciunt!</p>
  </v-col>
</template>

<script lang="ts">
import Vue from "vue"

export default Vue.extend({
  name: "DataTable",
  data: () => ({
    hideFooter: true,
    desserts: [1, 2, 3],
    limit: 100,
    loading: false,
    headers: [
      {
        text: "Dessert (100g serving)",
        align: "start",
        sortable: false,
        value: "name"
      },
      { text: "Calories", value: "calories" },
      { text: "Fat (g)", value: "fat" },
      { text: "Carbs (g)", value: "carbs" },
      { text: "Protein (g)", value: "protein" },
      { text: "Iron (%)", value: "iron" }
    ] as Array<{ text: string; align: string; sortable: boolean; value: string }>,
    childData: { tab: "Tenaaaaa", content: "Tab 10 Content" }
  }),
  methods: {
    handleDataFc: function () {
      this.$emit("eventName", this.childData)
    }
  }
})
</script>

<style></style>
