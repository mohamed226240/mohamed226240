<!DOCTYPE html>
<html lang="en">
   <head>
      <meta charset="UTF-8" />
      <meta http-equiv="X-UA-Compatible" content="IE=edge" />
      <meta name="viewport" content="width=device-width, initial-scale=1.0" />
      <title>Document</title>
      <style>
         body.active {
            overflow-y: hidden;
            background: #fff;
         }
         body::before,
         body::after,
         .content.active {
            content: "";
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            visibility: hidden;
         }
         .content.active {
            z-index: 1000;
            background: #fff;
            visibility: hidden;
         }
         body::before {
            background: #333;
            animation: background_animate 0.8s ease forwards;
         }
         body::after {
            background: #ccc;
            animation: background_animate 0.8s ease 0.4s forwards;
         }
         .content.active {
            animation: background_animate 0.8s ease 0.7s forwards;
         }
         @keyframes background_animate {
            0% {
               top: 100vh;
            }
            5% {
               top: 90vh;
               visibility: visible;
            }
            99% {
               top: 0;
               visibility: visible;
            }
            100% {
               /* position: relative; */
               visibility: visible;
               position: absolute;
            }
         }
      </style>
   </head>
   <body class="active">
      <div class="content active">
         <h1>Content</h1>
         <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Rem
            assumenda vitae cumque aspernatur nulla odio sapiente recusandae qui
            minus. Praesentium nobis quo tempora, dolor nesciunt minima repellat
            nemo autem voluptates sit sapiente, quisquam reprehenderit optio
            sunt eaque esse voluptatem soluta nam quae explicabo similique ad!
            Eum debitis iste reprehenderit. Dolorem suscipit illo, cupiditate
            debitis consectetur reiciendis animi nihil fugit vero modi, error
            optio voluptas unde repudiandae exercitationem eligendi sint placeat
            odio recusandae quia quo! Cumque odio neque ut voluptas esse
            excepturi laborum architecto perferendis consequuntur sequi. Neque,
            earum iste dolore beatae distinctio velit a cumque, odit laudantium,
            repellat placeat possimus?

            <br />

            Lorem ipsum dolor sit amet consectetur adipisicing elit. Qui fugit
            cupiditate perspiciatis nihil, dolore, nostrum impedit dolor vero
            fuga quia molestiae veniam minima quae voluptatum iure laudantium
            totam repellat alias natus architecto possimus esse ratione tenetur
            labore. Maxime fuga quaerat doloremque! Corporis assumenda culpa
            soluta, beatae veniam totam fuga provident dolor minima dolorum,
            necessitatibus sequi, non mollitia molestiae maiores ex natus
            possimus modi ipsam autem hic sed quae corrupti? Deleniti
            necessitatibus veritatis reprehenderit nostrum corrupti obcaecati
            ipsam alias sunt laboriosam dolorum ullam tempore labore nisi rerum
            impedit aut id facilis provident vero ex harum, libero sapiente
            voluptatum pariatur? Excepturi, alias?

            <br />

            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Impedit
            eius tempora enim illo porro ab commodi, quo rem corporis officia
            incidunt earum deleniti ratione hic quod! Minus, fugiat? Error
            dignissimos aliquam quas velit tempora eum voluptatibus, aut
            inventore necessitatibus, eveniet, culpa laborum quam facere ipsum
            autem. Qui quos, quae quia, id nihil dolore autem ea porro expedita
            ipsam repudiandae quis tenetur ab, nostrum maxime placeat? Eos
            laborum sequi accusantium deleniti recusandae illum ex quam enim cum
            id, a dicta libero consequuntur delectus, voluptatibus tempore earum
            totam maxime blanditiis assumenda, obcaecati quod similique quidem.
            Error at eum ratione dicta nam facilis, distinctio laudantium
            temporibus officia maiores beatae impedit laborum consectetur
            incidunt iusto ipsa inventore. Dolor voluptatem accusantium eius
            minus possimus suscipit vero quas ipsa dolorum! Tenetur voluptas
            non, nesciunt natus totam sint, dolorem unde maiores ea accusantium
            cum placeat adipisci ipsum magnam dolore, at minima ratione
            cupiditate architecto quasi fugiat. Rerum harum temporibus quia quas
            quae maiores, provident odit neque, a facere doloribus vel! Iste
            dignissimos architecto rem debitis rerum? Alias, blanditiis
            consequatur rerum hic ut tenetur cum odio, quasi fugiat eius quod
            ipsa debitis voluptatibus ullam dolorem veniam placeat, vitae
            provident omnis at iure quidem ipsam harum obcaecati! Optio impedit
            sunt officiis, qui voluptatum ratione nemo deserunt, eum facere,
            laboriosam a magni animi! Rem placeat eligendi numquam, quos
            doloribus debitis eos cum obcaecati iste dolore aspernatur
            voluptatem expedita minus earum veniam atque, ipsa doloremque ullam
            minima perspiciatis. Eligendi quibusdam totam quod aperiam amet iure
            est aut rem perspiciatis veniam! Possimus quos maiores minima
            temporibus voluptatum tenetur asperiores, consequatur optio fugiat
            sed distinctio quam ullam excepturi repudiandae saepe voluptatem
            provident, voluptas iusto, a porro. Iste ducimus quaerat adipisci
            illum cum id magnam, odit aperiam quia deserunt dignissimos, quos
            architecto possimus minima reprehenderit hic. Quisquam fuga soluta
            hic nam voluptate reiciendis quis alias ea consequatur harum? Ab
            distinctio molestias molestiae sed perferendis aspernatur repellat
            aliquam quam voluptates nobis a ducimus magnam corrupti perspiciatis
            quidem, incidunt iste doloremque debitis quis maiores? Quasi saepe
            eaque cupiditate neque dolorem ea facere maxime voluptatem vel
            reprehenderit quo animi quod voluptas aliquam, explicabo at? Dolore
            suscipit animi officiis aliquid incidunt atque, obcaecati saepe
            distinctio reiciendis recusandae eveniet totam ea ad dolores.
            Veritatis nesciunt rem illum culpa! Libero eius a voluptas
            praesentium possimus quis, eligendi atque totam obcaecati iusto
            vitae vero sit voluptatum nobis accusantium similique repellendus
            natus odio adipisci labore dolorum odit. Nam repudiandae quae
            maxime? Voluptatibus?

            <br />

            Lorem ipsum dolor sit amet consectetur adipisicing elit. Iusto
            perferendis dolores iste nostrum facilis necessitatibus sint magni
            aspernatur. Quos expedita accusamus fugit nostrum quisquam assumenda
            dolore a, nisi magni ratione deserunt atque iusto fugiat illo ab
            quam iure repellat mollitia magnam explicabo laborum impedit.
            Nostrum facilis quam ab omnis nobis. Id ea saepe minima aperiam
            corrupti voluptate non nam in. Officiis, sequi. Aperiam recusandae
            porro, accusamus quia laudantium consequatur sint! Quia praesentium
            aliquid eveniet explicabo accusantium eos nam animi nihil ad eum
            reiciendis consectetur, minima beatae cum harum vel? Iusto molestiae
            corrupti, eveniet reiciendis maiores doloremque itaque recusandae!
            Atque corrupti debitis exercitationem ex repudiandae eos mollitia
            culpa cumque quas perspiciatis! Aliquam explicabo consequatur atque!
            Minima nam aut quis nostrum vitae assumenda odio voluptate
            voluptatum natus numquam, et vero perspiciatis, tempore quisquam,
            soluta veniam commodi sunt sed quos? Eius nisi tempore delectus odio
            nobis vel blanditiis a nemo! Placeat ea unde, iste modi rem
            consequuntur sunt alias facere asperiores quod iusto cum hic officia
            enim, ratione velit! Beatae porro illo cum eveniet ipsum quis
            cupiditate quo iste dolor sequi voluptatibus nam ipsam, odio,
            labore, totam incidunt. Ab quas dolorum beatae eligendi quae?
            Veritatis obcaecati incidunt, omnis quibusdam exercitationem
            recusandae reprehenderit earum.

            <br />

            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Maxime
            dolorum ratione soluta, mollitia minus quasi perferendis nihil fuga
            explicabo illo alias ex? Aliquam ratione saepe molestias tenetur
            excepturi illo adipisci voluptas nobis ipsam, odio eos asperiores
            eveniet ducimus iusto natus repellat vitae magnam totam voluptate,
            corporis harum blanditiis reiciendis et. Deserunt quidem ipsam unde
            nobis non dolorem laboriosam ipsa distinctio eum reiciendis,
            voluptatum libero nemo, voluptas saepe provident mollitia modi
            cupiditate eius aliquam animi. Dolor vitae neque excepturi quaerat
            temporibus explicabo, quisquam inventore consequatur a doloremque id
            voluptas consectetur reprehenderit et soluta nesciunt eius
            praesentium? Repellendus quisquam fuga optio dignissimos cum laborum
            nam velit alias, ullam eaque hic voluptates cupiditate quidem autem
            officiis, error dicta tempore doloribus similique inventore
            consequatur nesciunt eveniet doloremque explicabo! Ipsum sapiente
            ipsa praesentium neque corrupti optio corporis fugit eaque culpa ea
            error at voluptate alias dignissimos suscipit commodi sequi,
            possimus libero tenetur excepturi. Labore voluptates porro adipisci
            ullam incidunt hic cum. Molestias, reiciendis debitis adipisci
            quidem quas iste exercitationem qui labore nesciunt vero at alias,
            laboriosam natus nulla voluptatibus sint ab quos pariatur maxime
            tenetur impedit atque? Libero illo corrupti incidunt sint alias!
            Eius ut eveniet, eaque nemo doloremque consequatur est
            necessitatibus velit odit sit voluptatem molestiae perspiciatis,
            cupiditate eos quos dolores tempore esse rerum officiis laborum.
            Animi consectetur consequuntur similique. Repellat dolores neque
            quibusdam facere enim! Numquam nemo pariatur unde odio illo quidem
            possimus eius sit quibusdam? Suscipit officia dicta eligendi sed
            voluptate. Voluptates voluptatum quam quos distinctio, sit provident
            ratione explicabo culpa eius quae illum impedit aspernatur obcaecati
            dicta adipisci dolorem ducimus a itaque autem minus blanditiis
            necessitatibus? Dolorum tempora porro voluptatibus nemo iste facere
            distinctio? At doloribus fuga autem veniam modi? Dolor
            necessitatibus vel ratione. Fuga magnam officia iste eveniet ipsum
            quas nobis laborum voluptatibus reiciendis deserunt. Et recusandae
            exercitationem accusamus laborum eos commodi eveniet optio tenetur
            necessitatibus, alias nesciunt repudiandae, ad iusto ut, officiis
            consequuntur aliquid. Exercitationem, deleniti cum impedit molestias
            quibusdam ea, hic necessitatibus, aut voluptatibus rerum ipsam.
            Architecto reprehenderit numquam similique optio iusto obcaecati,
            dolorum maiores enim cupiditate et dignissimos maxime veritatis
            voluptatibus sequi ullam nihil deleniti aperiam doloremque id culpa
            quae assumenda in, voluptatem illum! A quaerat quibusdam nostrum
            assumenda maiores dignissimos cum deleniti sunt quis, aut debitis
            sint similique necessitatibus. Animi voluptatum explicabo
            repudiandae. Temporibus ipsam ex autem quae maiores voluptate magni
            consequuntur tempore esse saepe perspiciatis consectetur, ipsa optio
            sit, minus qui aspernatur veniam earum dicta ducimus. Expedita autem
            placeat ad minus, harum consectetur ullam fugiat amet cupiditate
            consequuntur distinctio eligendi quaerat incidunt ut voluptatum
            eveniet doloribus fuga atque necessitatibus vel blanditiis ex
            ratione dicta. Doloremque voluptatum fugiat totam hic officiis
            assumenda ducimus quidem reiciendis cum odit sed, quibusdam amet
            molestias labore! Quibusdam voluptate, nam saepe, quam laboriosam
            soluta, ipsum sit ut aliquam doloribus quis minima ipsa inventore
            ratione iure consectetur? Expedita nulla ducimus minima asperiores,
            velit voluptatibus consectetur voluptate. Aliquid, corporis?
            Quibusdam, voluptas voluptatibus! Culpa nobis ratione, possimus
            aperiam eligendi commodi facilis explicabo iure nam nemo ea totam
            eum et rem sunt, accusamus tenetur ab.

            <br />

            Lorem ipsum dolor sit amet consectetur adipisicing elit.
            Consequuntur molestias animi provident pariatur, minus amet corrupti
            veritatis magnam incidunt harum nisi vero laboriosam inventore.
            Velit quia in, et delectus ex praesentium laudantium qui, at rerum
            enim vero numquam dignissimos possimus voluptatibus. Molestias
            deleniti perferendis soluta quibusdam sapiente, incidunt distinctio
            quae dicta qui debitis cumque fugiat libero sunt temporibus, quam
            ipsam blanditiis atque repellendus architecto aspernatur? Porro
            earum excepturi ducimus quas tempore commodi officia, ad accusamus
            animi veritatis explicabo non ea! Non voluptas rerum exercitationem
            laboriosam iste, dolores vitae perspiciatis eos asperiores fugiat
            magnam recusandae commodi natus est? Repudiandae eaque voluptatibus
            tenetur in esse fuga aspernatur omnis delectus ipsam adipisci? Eius
            dolores officiis, enim consectetur iste tempore vitae ut quos
            veniam, quia dolor. Perspiciatis, ipsa vitae iusto illo consectetur
            natus doloribus id fuga voluptatum aspernatur nihil aliquid
            accusantium magnam inventore sunt necessitatibus obcaecati nulla
            dolorum debitis molestiae eius quibusdam odio! Rerum, eum. Quos iure
            laboriosam accusamus deleniti sed aliquam nisi quia, impedit vero
            nesciunt adipisci expedita fugit a odio, dolore molestiae ipsum
            commodi accusantium? Quasi nihil autem explicabo doloremque odit
            nulla cum velit eligendi totam illum commodi, voluptatem aliquid
            quia quis a blanditiis, reiciendis perferendis saepe molestias
            dolorum iste, voluptas nisi. Fuga tempora nisi deleniti suscipit
            perferendis enim consectetur impedit exercitationem illo nihil
            incidunt, quis quidem aspernatur consequuntur neque perspiciatis
            tempore harum eaque soluta provident facere, aliquam quas error?
            Perspiciatis veritatis et quis sunt odit nesciunt, deserunt labore
            distinctio eius eos voluptate provident ut repellendus dolor
            eligendi earum expedita, sequi aliquam reprehenderit beatae ex
            velit, nam iure. Dicta, voluptatibus sapiente maiores, neque,
            delectus iste saepe suscipit tempora vel dolore molestiae libero!
            Facere alias recusandae possimus numquam nulla? Itaque impedit,
            nesciunt possimus reiciendis aperiam consequuntur laboriosam culpa
            explicabo aut velit veniam recusandae, libero accusantium aspernatur
            vel commodi. Vel unde aut veniam assumenda quos nobis quam illum qui
            ut a esse odio saepe dolore aliquam recusandae, dolor quas
            distinctio. Placeat dolorum quam minus explicabo consectetur
            doloremque facilis possimus, adipisci natus autem soluta magni
            ducimus dignissimos esse itaque reiciendis nulla magnam assumenda
            excepturi accusamus a blanditiis consequatur porro. Vel, sed quia
            architecto neque, porro saepe quo dignissimos necessitatibus facilis
            velit rerum minima. Suscipit dicta aspernatur delectus deleniti
            similique. Unde ut, autem odio, similique possimus, incidunt
            dignissimos eius voluptatum cumque temporibus et enim vel vitae
            repellat aperiam quaerat consequatur dolorem placeat sequi
            necessitatibus. Iusto porro reiciendis molestias recusandae eius
            explicabo quam officiis, voluptate, provident est qui, cum ipsa ab
            totam earum accusamus praesentium laborum ducimus possimus. Maxime
            aliquam quia fuga fugiat provident, necessitatibus dolorem nesciunt
            quam alias repellat laudantium non quo consequatur aspernatur
            suscipit facilis error, nostrum dignissimos quod distinctio? Cumque
            aliquid quaerat enim! Quo numquam cum fugit maxime soluta, illum
            quas, velit placeat veritatis ipsam eum et nesciunt pariatur
            quibusdam obcaecati, iusto perferendis explicabo alias. Saepe
            dolorem commodi voluptatibus voluptatum, eius repellendus quam
            suscipit reiciendis eveniet labore libero aut laborum illum maxime
            ullam adipisci! Rem vero porro quo hic voluptatum explicabo iure ad
            illo, earum dolor eaque nobis, nisi, quae officiis cupiditate saepe
            adipisci?
         </p>
      </div>

      <script>
         setTimeout(() => {
            document.body.classList.remove("active");
            document
               .querySelector(".content")
               .setAttribute("style", "position: relative;");
         }, 1300);
      </script>
   </body>
</html>
