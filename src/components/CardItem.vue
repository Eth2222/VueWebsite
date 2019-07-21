<template>
    <div style="padding:10px">
    <div class="card-item">
        <div class="mdc-card project-card" style="width:250px">
            <div class="mdc-card__primary-action project-card__primary-action" tabindex="0">
                <div class="mdc-card__media mdc-card__media--16-9 project-card__media" style="background-image: url(&quot;https://material-components.github.io/material-components-web-catalog/static/media/photos/3x2/2.jpg&quot;);"></div>
                    <div class="container-fluid" style="padding:10px">
                        <div class="project-card__primary">
                            <h2 class="project-card__title mdc-typography mdc-typography--headline6">{{title}}</h2>
                            <h3 class="project-card__subtitle mdc-typography mdc-typography--subtitle2">Subtitle</h3>
                        </div>
                    <div class="project-card__secondary mdc-typography mdc-typography--body2">Brief description of the project. include more context for the thing overall</div>
                        <div class = "row" style="padding:10px">
                            <div style="padding:0px 5px">
                                <div class="mdc-chip" tabindex="1">
                                    <div class="mdc-chip__text">Example Tag</div> 
                                </div>
                            </div>
                                <div class="mdc-chip" tabindex="2">
                                    <div class="mdc-chip__text">Another one</div>
                                </div>
                        </div>
                    </div>
            </div>
        </div>  
    </div>
</div>
</template>

<script>
export default {
    name: "CardItem",
    props:"project"
    
}
</script>

<style scoped>

</style>

