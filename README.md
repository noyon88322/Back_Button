## Back Button

Make Method In Java

   ```bash


    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_search);


      
              back_btn.setOnClickListener(v -> {
         onBackPressed();
       });



   ```
