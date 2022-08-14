# artasce website

vuetify firebase setup...

wanted nuxt, deploy to firebase issues...

nuxt for netlify... for now... firebase projects will use vuetify with vite for now... 

and for vuetify...

the ideals for vuetify include attributes on single lines!

```javascript
// .prettierrc

{
  "trailingComma": "es5",
  "tabWidth": 2,
  "semi": false,
  "singleQuote": true,
  "singleAttributePerLine": true
}

```
it definitely gives the vue projects a react look...

```javascript
        // i like this for vuetify...
        <v-row justify="center">
          <a
            v-for="(link, i) in importantLinks"
            :key="i"
            :href="link.href"
            class="subheading mx-3"
            target="_blank"
          >
            {{ link.text }}
          </a>
        </v-row>

        // and another....
        <v-row justify="center">
          <a
            v-for="(next, i) in whatsNext"
            :key="i"
            :href="next.href"
            class="subheading mx-3"
            target="_blank"
          >
            {{ next.text }}
          </a>
        </v-row>

```

