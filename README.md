# seekbar
#JAVA code
seekBar=findViewById(R.id.seek);
        seekBar.setOnSeekBarChangeListener(new SeekBar.OnSeekBarChangeListener() {
            @Override
            public void onProgressChanged(SeekBar seekBar, int i, boolean b) {
                Toast.makeText(MainActivity.this,"SeekBar changed"+i,Toast.LENGTH_SHORT).show();
            }

            @Override
            public void onStartTrackingTouch(SeekBar seekBar) {

            }

            @Override
            public void onStopTrackingTouch(SeekBar seekBar) {

            }
        });

// XML CODE
 <SeekBar
       android:id="@+id/seek"
       android:layout_width="match_parent"
       android:layout_height="wrap_content"
       android:layout_marginTop="50dp"
       android:background="@android:color/darker_gray"
       android:padding="10dp"/>

