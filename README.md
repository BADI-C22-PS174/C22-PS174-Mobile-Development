## REFERENCE LIBRARY

    //layout
    implementation fileTree(dir: 'libs', include: ['*.jar'])
    implementation 'com.android.databinding:viewbinding:7.2.0'
    implementation 'androidx.core:core-ktx:1.7.0'
    implementation 'androidx.appcompat:appcompat:1.4.1'
    implementation 'com.google.android.material:material:1.6.0'
    implementation 'androidx.annotation:annotation:1.3.0'
    implementation 'androidx.constraintlayout:constraintlayout:2.1.4'
    implementation 'androidx.lifecycle:lifecycle-livedata-ktx:2.4.1'
    implementation 'androidx.lifecycle:lifecycle-viewmodel-ktx:2.4.1'
    
    //firebase
    implementation 'com.google.firebase:firebase-database-ktx:20.0.5'
    implementation 'com.google.firebase:firebase-storage-ktx:20.0.1'
    implementation 'com.google.firebase:firebase-firestore-ktx:24.1.2'
    
    //recycleview
    implementation 'androidx.recyclerview:recyclerview:1.2.1'

    
    //test
    testImplementation 'junit:junit:4.13.2'
    androidTestImplementation 'androidx.test.ext:junit:1.1.3'
    androidTestImplementation 'androidx.test.espresso:espresso-core:3.4.0'

    //datastore
    implementation "androidx.datastore:datastore-preferences:1.0.0"
    implementation "androidx.lifecycle:lifecycle-viewmodel-ktx:2.4.1"
    implementation "androidx.lifecycle:lifecycle-livedata-ktx:2.4.1"

    //retrofit
    implementation 'com.squareup.retrofit2:retrofit:2.9.0'
    implementation "com.squareup.retrofit2:converter-gson:2.9.0"
    implementation "com.squareup.okhttp3:logging-interceptor:5.0.0-alpha.2"

    // Import the Firebase BoM
    implementation platform('com.google.firebase:firebase-bom:30.0.1')


    // Add the dependency for the Firebase SDK for Google Analytics
    // When using the BoM, don't specify versions in Firebase dependencies
    implementation 'com.google.firebase:firebase-auth:21.0.4-ktx'
    implementation 'com.google.firebase:firebase-analytics:21.0.0-ktx'
    implementation 'com.google.firebase:firebase-database:20.0.5-ktx'
    implementation 'com.google.firebase:firebase-storage:20.0.1-ktx'


    //design
    implementation "androidx.activity:activity-ktx:1.4.0"
    implementation 'de.hdodenhof:circleimageview:3.1.0'
    implementation 'com.google.android.material:material:1.6.0'
    
    //navigation
    implementation 'androidx.navigation:navigation-fragment-ktx:2.4.2'
    implementation 'androidx.navigation:navigation-ui-ktx:2.4.2'

    //myNotes
    implementation 'androidx.recyclerview:recyclerview:1.2.1'
    implementation 'androidx.cardview:cardview:1.0.0'
    implementation 'androidx.room:room-runtime:2.3.0'
    kapt 'androidx.room:room-compiler:2.3.0'


    //chart
    implementation 'com.github.AnyChart:AnyChart-Android:1.1.2'
    implementation("androidx.multidex:multidex:2.0.1")
    implementation 'com.github.PhilJay:MPAndroidChart:v3.1.0'
