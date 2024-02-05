# Closy - A extremly small iOS App that crashes itself upon launch to create IPS Logs for example.
Otherwise this app is pretty useless...

Whole App Code (in Swift) from ContentView.swift, nothing more is required:

import SwiftUI
struct ContentView: View {var body: some View {exit(0)}}
