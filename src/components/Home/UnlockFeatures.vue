<template>
    <section class="unlock-features">
        <h2>Dernières fiches de noms propres débloquées :</h2>

        <div class="last-nouns">
            <div class="new-noon">
                <div class="new-noon-img">
                <a :href=paris><img :src=paris width="150" alt="rouen"></a>
                </div>
                <div class="new-noon-text">
                    <h3>Paris</h3>
                    <p>
                        <b>Description:</b> "Capitale des Parisii, initialement construite sur la rive gauche de la
                        Seine,
                        puis nommée
                        Lutetia ou Loukotokia lors de l'installation romaine",<br>
                        <b>Nom gaulois:</b>"Parisios"<br>
                        <b>Composition::</b>"kario" (le Chaudron)<br>
                        <b>Traduction Littérale:</b> "La ville des Chaudronniers"<br>
                    </p>
                </div>
            </div>
        </div>
        <div class="last-nouns">
            <div class="new-noon">
                <div class="new-noon-img">
                <a :href=rouen><img :src=rouen width="150" alt="rouen"></a>
                </div>
                <div class="new-noon-text">
                    <h3>Rouen</h3>
                    <p>
                        <b>Description:</b> "La ville a été fondée sur la rive droite de la Seine durant le règne
                        d’Auguste.",<br>
                        <b>Nom gaulois:</b>"Rotomagos"<br>
                        <b>Composition::</b>"roto" (roue / course), "mag"(plaine / marché), "os"(suffixe de lieu)<br>
                        <b>Traduction Littérale:</b> "La PLaine de la Course de Char"<br>
                    </p>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
import Paris from '../../images/paris.jpg'
import Rouen from '../../images/rouen.jpg'

export default {
    components: { Paris, Rouen },

    data() {
        return {
            rouen: Rouen,
            paris: Paris
        }
    }
}
</script>