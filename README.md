# BottomDialog

### Use
```
private void showDialog() {
        BottomDialog bottomDialog = BottomDialog.create(getSupportFragmentManager());
        bottomDialog.setViewListener(new BottomDialog.ViewListener() {
            @Override
            public void bindView(View view) {
                
            }
        })
        .setLayoutRes(R.layout.xxx)
        .setDimAmount(0.5f)
        .setTag("xxx")
        .show();
    }
```
