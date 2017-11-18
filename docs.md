## SQL.RecordExists ( WhereField;WhereValue)```/**
 * 
 * tests to so if the record target by the SQL Where Field exists
 * often used to see if a record with a primary key exists
 *
 * @param {refernce} WhereField the field to search with SQL
 * @param {string} WhereValue
 *
 * @returns {boolean} 
 *
 * @module fm-sql-cfs
 * @see https://github.com/karbonfm/fm-sql-cfs
 * 
 * @history  2017-11-17, todd@geistinteractive.com
 *
 */```## SQL.GetTableName ( field)```/**
 * 
 * get the fully qualified SQL Name of a Table
 *
 * @param {reference} field
 *
 * @returns {string} 
 *
 * @module fm-sql-cfs
 * @see https://github.com/karbonfm/fm-sql-cfs
 * 
 * @history  2017-11-17, todd@geistinteractive.com
 *
 */```## SQL.GetRecordsAsJSON ( whereField;whereValue)```/**
 *
 * Searches the Table specified by the WhereField and retuns a JSON Array
 * uses SQL for the search and a field called AsJSON as the json object for the record
 *
 * @param {fieldReferece} whereField the field to search using a SQL "="
 * @param {fieldReferece} whereValue the value to searhc for
 *
 * @return {array}
 *
 * @module fm-sql-cfs
 * @see https://github.com/karbonfm/fm-sql-cfs
 * 
 * @history  2017-11-17, todd@geistinteractive.com
 *
 */```## SQL.GetFieldName ( field)```/**
 * 
 * get the fully qualified SQL Name of a Field
 *
 * @param {reference} field
 *
 * @returns {string} 
 *
 * @module fm-sql-cfs
 * @see https://github.com/karbonfm/fm-sql-cfs
 * 
 * @history  2017-11-17, todd@geistinteractive.com
 *
 */```## SQL.GetColumn2Fields ( columnField;whereField;whereValue;whereField2;whereValue2)```/**
 * 
 * get the values in a field using two WHERE field searches
 *
 * @param {reference} columnField
 * @param {reference} whereField
 * @param {string} whereValue
 * @param {reference} whereField2
 * @param {string} whereValue2
 *
 * @returns {string} the list of values in the field targeted with 'columnField'
 *
 * @module fm-sql-cfs
 * @see https://github.com/karbonfm/fm-sql-cfs
 * 
 * @history  2017-11-17, todd@geistinteractive.com
 *
 */```## SQL.GetColumn ( theField;whereField;whereValue)```/**
 * 
 * get the values in a field using two WHERE field searches
 *
 * @param {reference} columnField
 * @param {reference} whereField
 * @param {string} whereValue
 * @param {reference} whereField2
 * @param {string} whereValue2
 *
 * @returns {string} the list of values in the field targeted with 'columnField'
 *
 * @module fm-sql-cfs
 * @see https://github.com/karbonfm/fm-sql-cfs
 * 
 * @history  2017-11-17, todd@geistinteractive.com
 *
 */```