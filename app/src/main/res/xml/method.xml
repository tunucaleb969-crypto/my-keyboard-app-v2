package com.buddy.mykeyboard

import android.inputmethodservice.InputMethodService
import android.view.View
import android.widget.TextView

class MyKeyboardService : InputMethodService() {
    override fun onCreateInputView(): View {
        return TextView(this).apply {
            text = "My Keyboard is working"
            textSize = 20f
            setPadding(20, 40, 20, 40)
        }
    }
}
