# ACF JSON Field

CSV upload to JSON for Advanced Custom Fields.


## Usage

### Basic usage

    // Get encoded JSON
    $json = get_field('json_field');

    // Decode JSON to object
    $value = json_decode($json);

    // Use the values
    echo $value->something;

### Pass to javascript variable

    <script type="text/javascript">
      window.my_acf_name = <?php echo get_field('json_field') ?>;
    </script>

---

### Description

CSV upload for Advanced Custom Fields.

### Compatibility

This ACF field type is compatible with:

- ACF 5

### Installation

1.  Copy the `acf-field-csv-upload` folder into your `wp-content/plugins` folder
2.  Activate the Advanced Custom Fields: CSV plugin via the plugins admin page
3.  Create a new field via ACF and select the CSV type
4.  Please refer to the description for more info regarding the field type settings

### Changelog

Please see `readme.txt` for changelog

## Credits

This ACF field relies heavily on great package https://github.com/mholt/PapaParse
