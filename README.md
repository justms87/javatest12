package view;

import java.awt.event.ActionEvent;
import java.awt.event.ActionListener;
import java.awt.event.MouseEvent;
import java.awt.event.MouseListener;

import javax.swing.JButton;
import javax.swing.JFrame;
import javax.swing.JLabel;
import javax.swing.JTextArea;
import javax.swing.JTextField;


public class introView extends JFrame implements MouseListener,ActionListener {

	
	JLabel label;
	JTextField title;
	JTextArea content;
	JButton btn1,btn3;
	public introView() {
		//프로그램 소개뷰
		super("intro");
		setLayout(null);
		label = new JLabel("프로그램 소개");
		label.setBounds(300, 5, 300, 60);
		add(label);
		title = new JTextField();
		title.setText("금전적인 여유가있으신분");
		title.setEditable(false);// 글쓸수없게 만듬 쓸때는 true
		title.setBounds(200, 70, 300, 30);
		add(title);
		content = new JTextArea();
		content.setText("저희 프로그램은 공정하고 투명하게 아이를 위하여 기부할수있는 \n프로그램이며 어떠한 사람이든 아이에게 후원할수있는 자격이 주어집니다.\n"
				+ "또한 아이가 성장해가는 과정을 지켜볼수있으며 \n 최종목표는 후원하는 아이가 성장하여 혼자 살아갈수있게 \n도와주는것이 궁극적인 목표입니다.");
		content.setEditable(false);// 글쓸수없게 만듬 쓸때는 true
		content.setLineWrap(true);
		content.setBounds(200, 150, 400, 300);
		add(content);
		
		
		btn1 = new JButton("수정");
		
		btn3 = new JButton("돌아가기");
		btn1.setBounds(200, 500, 80, 30);
		
		btn3.setBounds(10, 10, 100, 30);
		add(btn1);
		
		add(btn3);
		setBounds(0, 0, 800, 600);
		setVisible(true);
		
		
		
		
		
	
	}
	
	@Override
	public void actionPerformed(ActionEvent e) {
		// TODO Auto-generated method stub
		
	}

	@Override
	public void mouseClicked(MouseEvent e) {
		// TODO Auto-generated method stub
		
	}

	@Override
	public void mousePressed(MouseEvent e) {
		// TODO Auto-generated method stub
		
	}

	@Override
	public void mouseReleased(MouseEvent e) {
		// TODO Auto-generated method stub
		
	}

	@Override
	public void mouseEntered(MouseEvent e) {
		// TODO Auto-generated method stub
		
	}

	@Override
	public void mouseExited(MouseEvent e) {
		// TODO Auto-generated method stub
		
	}

}
