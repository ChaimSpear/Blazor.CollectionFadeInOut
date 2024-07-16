# Blazor Collection Fade In Out
Blazor Component for collections to Fade In and Out using Blazor and some javascript

Sample on Blazorfiddle: https://blazorfiddle.com/s/wvjwyha1

Usage:
```html
<CollectionFadeInOut Items="$Collection or List$" Context="$name of your contect items$"
    OnShowedAllItems="$optional method to call once all the collection items have been faded in and out$"
    ViewableSeconds=$optional value for the display duration in seconds for each item, default is 5 (seconds) $>
    <ItemTemplate>
        $put your own html\tags\components to display the items$
    </ItemTemplate>
</CollectionFadeInOut>
```
