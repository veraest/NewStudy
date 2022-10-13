package com.example.logcat

import android.os.Bundle
import android.util.Log
import androidx.appcompat.app.AppCompatActivity


class MainActivity : AppCompatActivity() {
    val TAG = "lifecycle"
    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        setContentView(R.layout.activity_main)
        Log.d(TAG, "Уронили мишку на пол")
    }

    override fun onStart() {
        super.onStart()
        Log.d(TAG, "Оторвали мишке лапу")
    }

    override fun onResume() {
        super.onResume()
        Log.d(TAG, "Всё равно его не брошу")
    }

    override fun onPause() {
        super.onPause()
        Log.d(TAG, "Потому что он хороший)")
    }
}
