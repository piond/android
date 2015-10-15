# android
FRAGMENT TUTORIAL
- Layout -> Add FrameLayout (main_activity.xml)
- getSupportFragmentManager().beginTransaction().add(R.id.container, new MainFragment()).commit(); (main_activity.java - class)
- Add new class Fragment -> extends Fragment
- public View onCreateView(LayoutInflater inflater, ViewGroup container, Bundle savedInstanceState) {
    return inflater.inflate(R.layout.fragment_main, container, false);
  }
