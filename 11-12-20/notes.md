## rxjs
`switchMap`:
* Has a cancelling effect.
* Will cancel previous operations if something fails.
* Works well for "typeaheads" and autocomplete features

`mergeMap`:
* Will let previous operations finish if something fails.
* Can potentially cause memory leaks if inner observables are long lived.
* Works well if you want to flatten inner observables and control inner subscriptions.
* Works well if you want to flatten inner observables and control inner subscriptions.
