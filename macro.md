bool process_record_user(uint16_t keycode, keyrecord_t *record) {
  switch (keycode) {
    case ST_MACRO_0:
    if (record->event.pressed) {
      SEND_STRING(SS_LGUI(SS_TAP(X_C)));
    }
    break

    ...
  }


enum custom_keycodes {
    ...

  ST_MACRO_0,
};