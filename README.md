# uiTableFilter

- jquery plugin for filtering table rows

This is fork of http://github.com/gregwebs/jquery-uitablefilter by Greg Weber

## usage

              var t = $('table')
              $.uiTableFilter( t, phrase )
            

arguments:

    * jQuery object containing table rows
    * phrase to search for
      - If the phrase contains spaces it will be broken up into separate words that must all match a row

optional arguments:
              $.uiTableFilter( t, phrase, options )

    * column to limit search too (the column title in the table header)
    * column_numbers to limit search too
    * ifHidden - callback to execute if one or more elements was hidden


## Warning:

* expects a thead and tbody element
