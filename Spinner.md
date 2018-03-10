#Initialization

       ArrayAdapter provinceAdapter = new ArrayAdapter<>(getApplicationContext(), android.R.layout.simple_spinner_dropdown_item, provinces);

       provinceSpinner.setAdapter(provinceAdapter);