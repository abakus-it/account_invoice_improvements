This modules adds some functionalities to the invoicing process for AbAKUS.
---------------------------------------------------------------------------
    - it adds a field in the invoice form with the next invoice number.
    - it auto copies the supplier ref number to the bank transfer communication field.
    - it checks if the supplier invoice number already exists.
    - it adds a group by in account.move.line that groups by journal entry.
    - it changes the fields order in the treeview of account.move.line.
    - it adds a filter that filters on special journals and accounts
    - it checks if all the lines of the invoices contains at least one tax
